---
layout: default
---
# Translation of DATS
> Author: Immortal.S
> 
> Language: Chinese(simplified) -> English
> 
> Version: 7.761

## Farming
- 开始 Start
- 停止 Stop
- 保存配置 Save Config
- Bind Method:
    - 绑定最前端游戏 Bind Foremost DMO
    - 新建游戏 Start New DMO
    - 有何区别 Difference
        - Bind Foremost DMO: dats will bind the foremost window of DMO
        - Start New DMO: dats will start a new DMO and bind it

### 基本 - Base

#### 技能 - KeyPress
- 按键间隔 Delay(ms)
- 可自定义按键 (1-8, F1-f8)

#### 进化 - Evolution
- 自动进化 AutoEvolve
- 进化顺序 Evolve Order
- 有光环 DigiAura
- 进化设置说明 Description
    - 信息 Information
    - Evolve Number(1~9) according to Evolution Slot
    - Example: Alphamon - 3 or 111, Omegamon X - 431 or 311
#### 自动登录 - Login
- 掉线重连 AutoRelogin
- 游戏路径 DMOPath
    - 打开 Browse
- 账号 ID
- 密码 Pwd
- 二级密码 SecPwd

#### HP & Timed Out
- Only attack Digimon with 100% HP
- Only attack Digimon with less than [50%] HP
- Attack Timed Out (second): 10 (>=10)
- 取结晶 Auto Create Attribute from Your Digimon

#### Setting
- 指定好友上线时离开 Leave when friends online
- 指定好友 Select
- 自动任务 Auto quest
    - [Main Quest] Yokohama
    - [Main Quest] FileIsland-ServiceContinent-Tokyo
    - [Main Quest] Maze Entrance-F4
    - [Subquest] Verdendi - XAI Ver I
    - [Daily] Quests of Maze Key
    - [Daily] Diablomon
    - [Daily] Shinjuku-Digital Area
    - [Daily] RB Ticket
- 开启穿墙 Through wall
- 竞技场点下一关直到 x 关 Colo auto next stage until $x$

### 挂机 - Bot
- 定点打怪 Single Point
    - 频道 channel
        - 默认 default
    - 坐标 coord.
    - 获取 get
    - 范围 range
    - 原地打怪 in range
- 多点打怪 Multi Point (set 'range' and 'in range' at Single Point)
    - 标签 label
    - 坐标 coord.
    - 获取 get
    - 频道 channel
        - 默认 default
    - 挂机时长超时换点 duration
        - 时 h
        - 分 m
        - 秒 s
    - 附近没怪换点 no monster
    - 附近有人换点 meet other tamer
    - 增加 add
    - 删除 del
    - 保存 save
    - list
        - 选中 Y/N
        - 标签 label
        - 坐标 coordinate
        - 频道 ch
        - 挂机时长 duration
        - 无怪 Monster
        - 有人 tamer
- 追 boss 模式 Raid Boss
    - 信息 Information
    - Go next point when raid boss killed
    - Don't check 'no monster' in this method
- 说明 info
    - Order: Loops of Y-Line
    - The condition of changing points: duration, no monster, meet other tamer
    - List(Y/N): Left Click to select the specific line, then right click to choose Yes or No
    - Save: select the specific line then modify the settings and click save button

### 保护 - Recovery
- 吃药 Restoration Items (1-8, F1-F8)
    - tamer ds $\le x\%$ press 3
    - digimon HP $\le x\%$ press 3
    - digimon DS $\le x\%$ press 3
    - XG below $\le x\%$ press 2
- 人物技能 Tamer Skill (1-8)
- Buff or Exp Items
- IC Skill
    - interval 45 sec.

### 选怪 - Digimon
- 刷新附近怪物 Refresh nearby digimon list
- 打地底 Underground hit
- 反击主动怪 Counterattack aggressive digimon
- 优先攻击右侧列表靠后的怪 Prioritize attacks on the bottom monsters in the right List
- 清空 Clear

### 清理 - Item
- Line One
    - 刷新背包物品 refresh inventory 
    - 显示丢弃物品 discard list
    - 自动捡物 auto pick
    - 全部捡 pick all
    - 指定捡 pick specifically
- Line Two
    - 获取回收商人信息 load NPC
    - 自动回收 auto return
    - 一键丢弃 - discard - discard items according the list below
    - 一键回收 - return - return items according the list below
    - 信息 Info
        - 请先停止挂机或其他工具 Please stop bot or any other tools
        - 请先选中 回收商人 Please choose return-NPC first and stay close enough
- List
    - 位置 C/R
    - 名称 Item
    - 数量 NUM
    - 回收费用 Return(B)
    - 扫描费用 Scan(B)
    - 丢弃 Discard
    - 回收 Return

### 组队 - Party
- 开启组队功能 auto party (party member need to set same channel)
- Party Obtain Method
    - 先进行攻击者获得 The first attacker obtainment
    - 依序获得 Sequential obtainment
    - 自由获得 Free obtainment
    - 随机获得 Random obtainment
- 我是队长 Leader
    - 队员信息 Member ID
        - ID 1
        - ID 2
        - ID 3
- 我是队员 Member
    - Only accept party invitation from xxx
    - keep blank if not required

### 工具 - Tool
- Notice: Stop botting when any tool is running
- 状态 Status
    - Succeed
        - 成功
        - 完毕
    - Failed
        - 不足
        - 失败
#### 工具1 - Tool1
- 加速 Accelerate
    - 快速回收扫描鉴定 Fast Scan/Return
- 多开 - Multi Dmo - start a new DMO with new dmo.exe path from Base
    - 打开游戏 activate function
- 自动扭蛋 - Rare Machine - auto draw item from specific Rare machine or Memory machine
    - 快速扭蛋 - 移除 - old rare machine which should have been removed
    - 稀有扭蛋 - auto draw - Any Rare Machine
        - Info: Open Rare Machine First, then click the button
- 吃叶子 - Auto Scale- auto using fruit, ygg or something like this until the **Size** you set
    - 使用说明 Info
        - place the fruit @(1,1) of Inventory then click the "获取叶子ID - get fruit" to get fruit item ID
        - set the $size$ you want
        - click "吃叶子 - run"
        - wait until you got desired size or run out of fruits
    - 吃叶子 run
        - $x$ 以上（包含）停止, size $\ge x$
    - 获取叶子ID, get fruit, Get the id of fruit you want to use
- 快速点击 Fast Click - auto fast click item you want
    - 使用说明 info
        - place the item @(1,1) of Inventory
        - click the "获取道具ID - get item" to get ID of the item
        - click "快速点击-run" to start auto click
    - 快速点击 run
    - 获取道具ID - get item- Get the id of item you want to click
- 刷卡模式 Auto MC
    - **Botting Method**
    - 使用说明 info
        - place the MC @(1,1) of Inventory
        - Click "获取道具ID - get item" to get ID of the monster card which you will use
        - Choose "刷卡模式 - activate" to activate the botting method
        - **Click "开始"** to start botting Monster Card
    - 刷卡模式 - activate
    - 获取道具ID - get item
- 转圈 Revolve, using in dungeon
    - 开始转圈 run
    - 转圈范围 radius
- 自动换白色叶子 - Auto Exchange - auto exchange white lucky Leaf in FIW
    - 开始换 run
#### 工具2 - Tool2
- 自动孵化 - Auto Hatch - auto hatch until the specific level
    - 刷新背包蓝蛋 - get egg - Refresh the digiegg list of your inventory
    - 自动孵化(Button) run
    - Level
        - 到 5 阶 stop until level 5
        - 到 4 阶 stop until level 4
        - 到 3 阶 stop until level 3
- 手动强化 - Enchant - fast enchant your digimon manually
    - method - enchant choice method
        - 随机翻牌 random choose 1/14 when enchant
        - 上x - up x - the xth choice up there, from left to right
        - 下x - down x - the xth choice down there, from right to left
    - 克隆备份装备 - load
        - First click to upload backup item
        - second click to upload clone(D~S)
    -  强化 - enchant - try to enchant(fast)
    -  快速强化 - faster - enable fast enchant when you enchant in dmo manually, dont have to click "强化-enchant" in dats to achieve fast enchant
- 自动强化 Auto Enchant
    - settings
        - 等级大于等于 x 使用备份 use backup item when $stage\ge x$
        - 等级等于 x 停止强化 stop auto-enchant when $stage == x$
    - Function
        - 普通强化 - normal - auto enchant according the setting in Auto-Enchant
        - 极限强化 - perfect - auto perfectly enchant according the setting in Auto-Enchant, will reach the extreame status of each stage
    - 说明 info
        - prepare all the enchant material, including cloneD~S, backup, reset capsule and Tera
        - Stage downgrade method
            - $stage\le 6$: use reset capsule
            - $stage> 6$: downgrade when enchant failed
        - perfectly enchant:
            - please make sure the enchant stage before using this function is already perfect!
            - please make sure the enchant stage is perfect when auto perfectly enchant stop abnormally
- 进化 Evolution
    - 无 CD 进化 - no CD - evolution without cd
- 自动奶 - Auto Heal - place all healing IC @F3
    - info:auto using healing IC in different evolutionary stage
    - 进化顺序 - evo order - the order of evolutionary to use IC
        - 1~8 correspond to evo slot
        - 9 degenerate
        - Example(agumon): 1119,agumon-greymon-metalgreymon-wargreymon-agumon-...
    - 自动奶 run
- 改模
    - 开启无动作 - noAction on - easy to use asb
    - 关闭无动作 - noAction off 
    - 穿墙 - through wall - enable to across the wall in game, need to change map after click the button to activate the function
### 回话 - Reply
- Reply random sentence below when someone whisper you
- 添加 add
- 删除 remove

### Boss - Boss
- Botting Method
- 开启自动追BOSS - auto boss
- settings
    - 优先追未知时间的Boss - unknown first -chace the unknown-time-remain boss first
    - 骑乘 - riding - use riding function when chacing boss
    - 固定路线 - regular - same order in every run
    - 上传固定路线 - upload - upload new stable-order
        - please make sure the accuracy of new order, or you will be punished
    - 刷新Boss信息 - update - refresh the boss info list
        - 地图 map
        - 频 channel
        - 怪物 monster
        - 上次死亡时间 - death - the time of last death
        - 刷新剩余时间 - remain - reamain remain time of respawn
        - 追 - chace - left click to chose then right click
- Info:
    - Choose "开启自动追BOSS - auto boss"
    - Adjust settings
    - Click "开始 - start" start botting
### 寻路 - Portal
- 寻路方式 Jumping Between Maps
    - 炸弹传送 Booster
    - 获取背包炸弹 - get booster - Get jumping bomb from inventory
    - 会员传送 vip
    - 走路 walk
- 回城消疲劳 Recover fatigue in dats
    - 疲劳满时炸弹回城 jumping to dats
    - 疲劳满时 VIP 回城 vip jumping to dats
    - 获取背包炸弹 get booster
    - 挂机时点击立即回城消疲劳 recover fatigue now
    - 脱衣服消除疲劳后，吃药 3 - uncloth, recover item 3
- 自动领票 Auto Daily Ticket - Refresh inventory or change channel to show the ticket
    - 会员传送 vip
    - 炸弹传送 booster
    - 开始领票 run
    - 停止领票 stop


### 日志 - Log

------

## Dungeon

### 基本 - Base

#### 技能 - KeyPress
- 按键间隔 delay(ms)
- 可自定义按键 (1-8, F1-f8)

#### 进化 - Evolution
- 自动进化 AutoEvolve
- 进化顺序 Evolve Order
- 有光环 DigiAura
- 进化设置说明 Description
    - 信息 Information
    - Evolve Number(1~9) according to Evolution Slot
    - Example: Alphamon - 3 or 111, Omegamon X - 431 or 311

#### 自动登录 - Login
- 掉线重连 auto relogin
- 游戏路径 DMOPath
    - 打开 browse
- 挂机频道 channel
- 账号 ID
- 密码 Pwd
- 二级密码 SecPwd

#### 技能 Skill (Specific Digimon)
- 说明 Description
    - Four Holy Beasts(Hard) and Digimon Below Only
    - 确定 OK

### 挂机 - bot

#### Line 1
- 开启穿墙 through wall
- 开启无动作 no action
- 转圈模式 revolve
- 说明 info
    - Only leader will revolve when party
    - Member can set HP limit to attack when party
    - Leader need to save configuration after modify coordinate
    - Member need to save configuration after modify HP limit
    - You can restart bot at any stage of dungeons or outside dungeons

### 保护 - Recovery
- 吃药 Restoration Items (1-8, F1-F8)
    - tamer ds $\le x\%$ press 3
    - digimon HP $\le x\%$ press 3
    - digimon DS $\le x\%$ press 3
    - XG below $\le x\%$ press 2
- 人物技能 Tamer Skill (1-8)
- Buff or Exp Items
- IC Skill
    - interval 45 sec.
### 组队 - Party
- 开启组队功能 auto party (party member need to set same channel)
- Party Obtain Method
    - 先进行攻击者获得 The first attacker obtainment
    - 依序获得 Sequential obtainment
    - 自由获得 Free obtainment
    - 随机获得 Random obtainment
- 我是队长 Leader
    - 队员信息 Member ID
        - ID 1
        - ID 2
        - ID 3
- 我是队员 Member
    - Only accept party invitation from xxx
    - keep blank if not required
- 队伍人数 At least x tamer enter the dungeon
    - keep blank if not required
### 回话 - Reply
- Reply random sentence below when someone whisper you
- 添加 add
- 删除 remove
### 寻路 - Portal
- 寻路方式 Jumping Between Maps
    - 炸弹传送 Booster
    - 获取背包炸弹 - get booster - Get jumping bomb from inventory
    - 会员传送 vip
    - 走路 walk
- 回城消疲劳 Recover fatigue in dats
    - 疲劳满时炸弹回城 jumping to dats
    - 疲劳满时 VIP 回城 vip jumping to dats
    - 获取背包炸弹 get booster
    - 挂机时点击立即回城消疲劳 recover fatigue now
    - 脱衣服消除疲劳后，吃药 3 - uncloth, recover item 3
### 日志 - Log