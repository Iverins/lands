# Lands是什么?

Lands 是一款独特的王国系统，可以通过游戏中的GUI进行高度的自定义配置，化繁为简，让您的玩家轻松上手。
从现在开始，探索无限的可能。

----

需要帮助？
Discord: https://discord.gg/B4MAJVk

# 安装

1. 关闭你的服务器.
2. 将从Spigot下载的 **Lands.jar** 放入 **/plugins** 文件夹里.
3. 开启服务器.
4. 编辑配置 | 你可以从 **/plugins/Lands** 中找到.
5. 重启服务器

### 注意

您可以使用 `/lands admin import` 从其它类似的插件中导入配置.

----

在安装更新之前，请关闭服务器.

# 入门

## 常见问题

**在阅读本条目之前，请先阅读 *从玩家开始* 条目再来阅读 **

**问:** 我有多片王国，如何选择其中一个？
**答:** 请输入 `/lands edit` 来选择或者输入 `/lands claim <王国>` .

**问:** 我有多片王国，如何选择其中一片王国进行编辑，而不要每一次都输入相同的命令.
**答:** 请输入 `/lands edit <王国>` 来选择.

## 从玩家开始

1. 可选:创建一个王国
 `/lands create <名字>`
2. 可选:进入选择模式 
 `/lands selection 或者服务器提供了一个选择工具.`
3. 可选:选择你要认领的区域的两个对角
 `用左键或者右键来选择`
4. 使用 `/lands claim` 来认领区块
 如果没有进入选择模式，它将会认领你所在的区块.
 如果没有创建王国，它将会以你的游戏ID来创建一个王国.
5. 打开王国菜单来管理你的王国
 `/lands menu`
6. 想要管理不同的王国
 `/lands edit <王国> 而后你输入有关于管理王国的命令都是关于这个王国的.`

----

### 选择一个王国进行编辑

请输入 `/lands edit <王国>` 来选择，而后你输入有关于管理王国的命令都是关于这个王国的.

### 信任玩家

请输入 `/lands trust <玩家ID> [区域|*|单个王国]` 来信任一个玩家，该玩家可以打开你的王国管理菜单. | 你也可以单击菜单里面的 `玩家信任` 来进行管理.

### 移除信任

请输入 `/lands untrust <玩家ID> [区域|*|单个王国]` 来移除信任一个玩家，该玩家将不能打开你的管理菜单. | 你也可以单击菜单里面的 `移除信任` 来进行管理.

### 为玩家开放权限

1. 输入 `/lands` 打开王国菜单
2. 点击 `爵位` 物品
3. 打开 `爵位` 设置菜单
4. 开始配置吧

### 给玩家升/降官

1. 输入 `/lands` 打开王国菜单
2. 单击 `玩家` 物品
3. 左键升官或右键降官

## 命令

**[] 代表可选 | <> 代表必选**

> `/lands help [页数]`
> `权限: lands.command.help`
> 描述: 打开帮助界面.

> `/lands claim`
> `权限: lands.command.claim`
> 描述: 认领区块

> `/lands create`
> `权限: lands.command.create`
> 描述: 创建一个王国

> `/lands accept <王国>`
> `权限: lands.command.accept`
> 描述: 同意一个王国的拉拢

> `/lands chat [王国] <信息>`
> `权限: lands.command.chat`
> 描述: 进入王国的聊天频道

> `/lands delete`
> `权限: lands.command.delete`
> 描述: 删除你的王国

> `/lands deny`
> `权限: lands.command.deny`
> 描述: 拒绝一个王国的拉拢

> `/lands deposit [王国] <数量>`
> `权限: lands.command.deposit`
> 描述: 将钱存入国库

> `/lands edit <王国>`
> `权限: lands.command.edit`
> 描述: 进入某王国的编辑模式,类似于 `/lands claim` 的命令将会以此王国为目标.

> `/lands info [王国]`
> `权限: lands.command.info`
> 描述: 查看有关王国的信息

> `/lands invites`
> `权限: lands.command.invites`
> 描述: 打开收到的邀请

> `/lands leave <王国>`
> `权限: lands.command.leave`
> 描述: 离开一个王国

> `/lands map`
> `权限: lands.command.map`
> 描述: 打开王国地图

> `/lands menu`
> `权限: lands.command.menu`
> 描述: 打开王国菜单

> `/lands menu here`
> `权限: lands.command.menu`
> 描述: 打开当前你目前所在的区块的王国菜单

> `/lands rename [王国] <新名字>`
> `权限: lands.command.rename`
> 描述: 为你的王国取新名字

> `/lands selection`
> `权限: lands.command.selection`
> 描述: 为一些行为设置一个区域
> 可以有的行为
> /lands claim
> /lands unclaim
> /lands leave
> /lands trust
> /lands untrust

> `/lands setrole <玩家> <区域,*> <官职>`
> `权限: lands.command.setrole`
> 描述: 为玩家设置一个官职,区域代表的是王国的子区域

> `/lands setspawn`
> `权限: lands.command.setspawn`
> 描述: 为王国设置一个重生点

> `/lands spawn [王国]`
> `权限: lands.command.spawn`
> 描述: 传送至一个王国的重生点

> `/lands teleport <X> <Z>`
> `权限: lands.command.teleport`
> 描述: 传送至一个区块(王国已经占有的)

> `/lands top`
> `权限: lands.command.top`
> 描述: 查看王国排行榜 

> `/lands trust <玩家> [区域,*]`
> `权限: lands.command.trust`
> 描述: 信任一个玩家

> `/lands unclaim`
> `权限: lands.command.unclaim`
> 描述: 取消占有当前的区块

> `/lands untrust <玩家> [区域,*]`
> `权限: lands.command.untrust`
> 描述: 取消信任玩家

> `/lands view`
> `权限: lands.command.view`
> 描述: 将王国边界可视化

> `/lands wild`
> `权限: lands.command.wild`
> 描述: 传送至荒野. 你可以在配置文件中设置

> `/lands withdraw [王国] <数量>`
> `权限: lands.command.withdraw`
> 描述: 从国库中取钱

> `/lands taxes`
> `权限: lands.command.taxes`
> 描述: 查看即将支付的税款

> `/lands rent`
> `权限: lands.command.rent`
> 描述: 管理王国租地费用



## 王国区域

### 什么是区域?

王国区域是一个在王国内部的一个类似于诸侯国的概念.这片区域是三维的,意思就是说它们不是指区块,而是指方块.你可以将这一片区域给玩家应用,类似于国中国一般.

### 创建新的区域

1. 首先,打开你的王国管理菜单 `/lands menu` ,然后点击 `区域物品` .(您的服务器可能会有一些不一样)

![AreaItem](https://static.complexstudio.net:10500/uploads/images/2021-02-04/ddfad52fd978a0cae9381dc857702b1d.png)

2. 现在点击进去,然后点击创建区域,并且在聊天框输入区域名字.

![AreaCreate](https://static.complexstudio.net:10500/uploads/images/2021-02-04/ac861de8e52fa9d442f10f8a6b5de0b1.png)

3. 之后，你会发现你打开了区域菜单，并且告诉你如何设置区域大小.

![AreaSize](https://static.complexstudio.net:10500/uploads/images/2021-02-04/b1b60e9d38f8f1bb7154f189b3444f75.png)

4. 当设置完毕后,它会实时显示区域大小给你,你可以根据你的需要进行更改,然后只需要再次输入 `/lands selection` 既可.

![AreaSelection](https://static.complexstudio.net:10500/uploads/images/2021-02-04/8ddea9824ca77f1903d2cd45d2461a73.png)

### 信任玩家&设置Flags

请再次打开区域菜单,你可以在这片区域信任一个玩家,或者编辑其它玩家能用的权限(类似于 Residence 的领地权限一般,称之为 Flags[标志]),而且,你可以为这片区域当成一个小王国.

![Flags](https://static.complexstudio.net:10500/uploads/images/2021-02-04/fa58080dda6381cc892a8c9b9341ec40.png)



## 租地制度

### 配置文件中的设置

```yaml
# 租赁/出售区域设置
# Rent = 玩家可以租用那一片区域
# Taxes = 受信任的玩家需要在每一段时间缴纳的税款
  rent:
    # 允许玩家设置可租赁的区域?
    rent: true
    # 允许玩家将区域卖了或者将王国卖了?
    sell: true
```

### 租赁牌子
----
#### 如何设置租赁牌?

![RentSign](https://static.complexstudio.net:10500/uploads/images/2021-02-04/b006b8bbbd2c17036923d93a3c93cdbd.jpg)

#### 说明

+ 以上例子:
  + 花费 **$200** 能租借 **5** 天. 
  + 最大可租借天数为 **50** 天.
+ 牌子可以使用: **d = 天** | **h = 小时** | **m = 分钟**
  + 如果没有写上,默认用 **d**
+ 你只能租出一片区域,对于卖出,默认是卖出一片区域(或者是卖出一整个王国,以下有说明)

#### 设置以后

![Result](https://static.complexstudio.net:10500/uploads/images/2021-02-04/50731d1e3cdd4c3a7ba9d01aa672a32b.jpg)

#### 说明

+ 当设置完成后,牌子将会变成这样且玩家可以使用牌子.
  + 想要租用这片区域,玩家只需右键它.
  + 想要增长时间,只需要再右键一下.
+ 取消租用
  + 租户可以使用 `/lands rent` 来取消他当前所在的区域的租用.
+ 取消租金
  + 区域的主人可以使用 `/lands rent` 来移除他所处于的区域的租金.

### 出售牌子
----
#### 如何设置出售牌?

![SellSign](https://static.complexstudio.net:10500/uploads/images/2021-02-04/655a08eca29d5edf4772f8cc46ed00ac.jpg)

#### 说明

+ 以上例子:
  + 花费 **$5000** 来买下整片区域.
  + 而后那个玩家将会成为那片区域的主人

#### 设置以后

![ResultSign](https://static.complexstudio.net:10500/uploads/images/2021-02-04/b75f2786499d655b8d48350390f8481f.jpg)

#### 说明

+ 设置完成后,玩家可以使用这个牌子了.
  + 想要买下这片区域,只需要点击这个牌子即可
+ 取消所有权
  + 买家可以站在该区域时输入 `/lands rent` 来取消这片区域的所有权.
+ 取消出售
  + 卖家可以挖掉这个牌子或者输入 `/lands rent` 来取消这片区域的出售.

## 战争系统

本章节将会深度剖析 **Lands** 的战争系统.

### 宣战

想要宣战,只需要输入 `/wars declare <王国>` 即可.
现在将会弹出一个菜单,询问您是否要设置战争赔款,如果敌人被打败,将会由敌人来支付这赔款.
单击 `发送` 按钮后,敌人将会收到你的战书以及相关信息,例如战争将于何时开始以及战争赔款的具体项目.

### 战前准备

发送战书后,战前准备时间将会开启.在这一段时间内,抵御者有时间为即将到来的战争做好准备,时间长短取决于你服务器的配置.两个王国的所有玩家都会定期收到有关消息,通过输入 `/wars info` 或者通过 `/wars` 打开战争菜单能够获取更为详细有关战争的信息.

### 战争打响

当战前准备时间结束以后,战争已经打响,两个王国的国民们将会饮血奋战.你的服务器可能启用了某些设置,比如防止玩家离线时敌对国不讲武德搞偷袭.通过输入 `/wars info` 或输入 `/wars` 打开战争菜单能够获取更为详细有关战争的信息.

### 战时

在战争期间,你可以入侵别人的王国并且从其的容器(箱子,熔炉,炼药锅等)中获取物品(但这些皆可配置).你甚至可以挖掉或者放置某些方块(同样,这也可以配置).另外,你还可以配置每个王国至少要在线多少人才能入侵土地的选项.

### 战争结束

你可以配置战争持续的最长时间,你可以在战争期间看到战争何时结束.击杀人数最多的王国将会获得胜利.获胜者将从败者国库中获得赔款(你也可以更改从其它渠道中获取).你还可以设置自定义奖励.如果两个王国的击杀人数一样的话,则双方将会和局,一点奖励都没有.而且,战后将会获得一个战争保护时间(这取决于你的服务器配置)

# 配置

## 常见配置问题

**问:** 我该如何在荒野中禁止破坏和PVP?
**答:** 你可以输入这个命令 `/lands admin wilderness` 来打开荒野管理菜单去修改荒野的 Flag

**问:** 如何才能使玩家只能在已占领的土地中飞行?
**答:** 请给予他们 `/fly` 的权限,但不要给他们 `fly.bypass` 的权限.同样,你需要在已占领的土地中启用 `fly` 的Flag.如果需要在荒野飞行,请使用 `/lands admin wilderness` 来修改Flag

**问:** 如何使领地边界可视化永久显示?
**答:** 请将时长设置为 `-1`,如果你想一加入服务器就能看到边界可视化,请按照以下来配置
```yaml
# /lands view 的配置
view:
    # 玩家是否一加入服务器就能看到王国边界?
    # 提示: 你可以将 duration_9 (或者更低) 设置为 -1 就能永久显示.
    join: true
    # 王国边界的显示市场.
    # 单位为秒 , 永久显示请设置为 -1
    duration_9: 60
```

**问:** 我的玩家无法设置王国,发生甚么事了,马老师.
**答:** 我一看,嗷,原来是没权限,Lands会提示您没有哪些权限.你只需要配置即可.

**问:** 我觉得信息文件的提示不好康,我想自己来.
**答:** 小妹妹不要在网上晒自己,要多学习提高自己的知识才是正事,那么就让哥哥告诉你,在 `plugins/Lands/Language` 文件夹就能找到.

**问:** 即使我禁用了PVP,但我还是想让我的玩家PVP.
**答:** 你可以打开这个设置
```yaml
# 不影响战争的战斗设置.
combat:
  # 战斗状态
  # 如果一个玩家攻击了另一个玩家，那么他将会进入 x 秒的战斗状态,
  # 无论他在哪里，玩家都可以攻击他.
  # 0s = 禁用
  tag-time: 15s
  # 同一个王国的人可以在荒野处发生内讧吗?
  # 注意: 此选项需要服务器重载 / 重启.
  ally-wilderness: true
```

**问:** 如何启用 / 禁用选择 / 占领工具?
**答:** 你可以在 `config.yml` 中找到这个选项,或者在 `GUI的语言文件` 中更改选择 / 占领工具
```yaml
# Lands是否给予每位新玩家 GUI语言文件 内的 选择 / 占领 工具?
# 如果你在 GUI语言文件 中设置工具的材质为 GOLDEN_HOE (金锄) , 则所有 金锄 都会变为 选择 / 占领工具.
# 这意味着玩家可以自己制作工具来 选择/占领 , 但是 , 即使你没有工具 /lands selection 也可以使用.
# 自动为玩家提供 选择工具 , 只需要告诉他们如何 占领 领土就行了,
# 他们可以右键 空气 来圈地 , 而不用点击 方块.
selection-tool: true
```

**问:** 如何让玩家在特定的区域中占领领土 (WorldGuard规定的区域)
**答:** 你只需要输入 `region flag [区域] lands-claim deny/allow` (deny = 拒绝 | allow = 允许) 即可 , 默认是 deny 的.

## 数据库

### 可用的数据库类型

+ **JSON**: 如果你不需要将数据与外部相连的话,我们建议使用 JSON.一般来说,推荐有经验的服主使用 **MySQL** .
+ **MySQL**: **MySQL版本至少要 5.8+**.旧版本无法使用,请改用 **JSON** , 如果你需要将数据库连接到外部或者使用备份系统,则建议使用 **MySQL** . 如果要使用 **MySQL** , 请确保设置正确(比如 最新版的MySQL , 连接限制, utf8mb4_0900_as_cs作为数据表编码等.) 注意: 请勿搞 `跨服数据库` , 这些数据表应该只连接**一个**Lands服务器.

### 将数据导出到 MySQL , 和 JSON

1. 强烈建议导出之前请清空数据库! **否则,将会遇到一些不可描述的问题**
2. 当然,如果要导出至 MySQL ,请确保在 Lands 配置中正确设置了数据库名称与密码.
3. 备份当前数据库. 完成之后,请输入: `/lands admin convert [json , mysql]`

## 玩家奖励

**你需要在配置文件中启用这个功能**

### 它是如何工作的

玩家可以在线每 x 秒就获得一次奖励,比如一个 `方块`.

### 配置

```yaml
time-reward:
  enabled_17: false
  # 时间设置
  # 多少秒后玩家应该获得
  # 王国内的一个区块或者自己王国多增一个区块或者多扩充一个玩家的奖励.
  # 注意: 时间单位是秒
  time:
    # /Lands claim
    chunks: 3060
    # 玩家可以加入的王国数量.
    lands: 43200
    # 最大的王国玩家 (一个王国最多能有多少个玩家?)
    members: 21600
    # 玩家可以创建多少个王国.
    # /Lands create
    lands-own: 86400
```

### 最大限制

可以设置玩家能够获得的最大区块奖励数量，详见：

[https://github.com/Angeschossen/Lands/wiki/Permissions#playtime-reward-permissions](https://github.com/Angeschossen/Lands/wiki/Permissions#playtime-reward-permissions)


## 王国排名

### 排名牌

创建一个排名牌你需要在牌子键入以下内容:

**第一行:** [lands]
**第二行:** top
**第三行:** 需要显示排名的数量

###  排名浮空字

要创建浮空字,你需要安装[HolographicDisplays](https://dev.bukkit.org/projects/holographic-displays/files),然后输入 `/lands admin hologram` 来获取浮空字的命令列表

**创建浮空字:**
`/lands admin hologram create`

**列出浮空字列表:**
`/lands admin hologram list`

**删除浮空字:**
`/lands admin hologram delete`

## LuckPerms 支持

如果你的服务器内安装了 [LuckPerm](https://www.spigotmc.org/resources/28140) 的话,那么,你便可以搭配它来更好地开发Lands的功能.

可用参数:

+ land = 王国名字
+ land_area = 区域名字

这里有两个参数来确定玩家在当前位置是否受到该王国的信任:

+ land_area_trusted = yes
+ land_area_trusted = no

### 实例

当玩家在某一个王国内,才能拥有的权限:
`/lp user Luck permission set test.permission land=landname`
王国名不区分大小写

当玩家在野外时才有权限
`/lp user Luck permission set test.permission land=wilderness`
注意: 你还可以设置 非(-) 来删除此权限

当玩家被信任时才能拥有权限:
`/lp user Luck permission set test.permission land_area_trusted=yes`

## 容器(GUI菜单)

GUI 文件在: `/plugins/Lands/Language`

我们的菜单可以所有语言都可以配置,菜单图标的位置都可以完全自定义.

有一些被隐藏的功能:
1. 禁用物品
    添加 `enable: false` 即可禁用
2. 设置 custom model data:
    添加 `model-data: 数字` 即可启用
3. 设置物品数量
    添加 `amount: 数字` 即可启用.

## 信息文件

信息文件在: `/plugins/Lands/Language`

### 用Title或者Actionbar显示信息

实例:
`pvp-warning: '&c你进入了PVP状态.'`

你只需要加一个 `#t#`(Title显示) 或者 `#c#`(Actionbar显示) 即可
`pvp-warning: '#t#&c你进入了PVP状态.'`

你可以加一个 `[newline]` 来代表 `\n`

### 禁用信息

实例:
```yaml
enter:
  land: '#t#&2&l{land}[newline]&3{title}'
  safezone: '#t#&2&l{land}[newline]{title}'
```

只需要留空即可.
```yaml
enter:
  land: ''
  safezone: ''
```

### 文本点击

你可以使每一个在聊天栏提示的消息都可以点击,这意味着你可以设置悬停文本等.请注意,这个不适用于 **前缀** .

1. 自定义文本的用法:
    `[T]自定义文本[/T]`
2. 悬停:
    `[T]自定义文本[H]悬停文本[/H][/T]`
3. 命令:
+ 执行命令:
  `[T]自定义文本[H]悬停文本[/H][C]lands help[/C][/T]`
+ 补全命令:
  `[T]自定义文本[H]悬停文本[/H][SC]lands help[/SC][/T]`

#### 现学现用

```
  [T]&7Player&3 {player} &7invited you to join their land&2 {land}&7.[H]&7Click to open your invites menu.[/H][C]lands invites[/C][/T] &7Taxes:&c${tax}
  [T]&2Accept &8[&8CLICK&8][H]&7Click here to accept this invite.[/H][C]lands accept {land}[/C][/T]
  [T]&cDeny &8[&8CLICK&8][H]&7Click here to deny this invite.[/H][C]lands deny {land}[/C][/T]
```

#### 显示图

![Display](https://static.complexstudio.net:10500/uploads/images/2021-02-05/89b3e3169a1ef4a0f6df4186128de2c9.png)

## 官职

Lands具有功能非常丰富的官职系统,该系统能让你的王国为每个官职设置不同的权限,并且能让你自己制定官职.你可以以服务器管理员的身份编辑/添加默认官职,玩家可以在自己的王国菜单内添加属于自己的官职.

### 添加 / 编辑默认官职

> 你可以在 `/plugins/Lands/role.yml` 中编辑现有的默认官职或者添加新的默认官职,这些官职将适用于新的王国.

实例:

```yaml
yourCustomDefaultRole:
  name: '&e自定义默认官职'
  # icon支持纹理 (推荐网站: https://minecraft-heads.com/) 和普通材质.
  icon: 'eyJ0ZXh0dXJlcyI6eyJTS0lOIjp7InVybCI6Imh0dHA6Ly90ZXh0dXJlcy5taW5lY3JhZnQubmV0L3RleHR1cmUvYjFhZGZkZjA3MTE3NWFkYWQ2NDRmZTRiM2E5NzMxYWM2YThmYTQ3NTExNjJlODEzOGM4OTlmYmFhNWZmMGI5In19fQ=='
  # 默认Flag设置,请注意,这些只适用于新建的王国,如果Flag有在上面的"Display"设置中,那么玩家可以对其进行更改.
  default:
    - BLOCK_PLACE
    - BLOCK_BREAK
    - INTERACT_GENERAL
    - INTERACT_DOOR
    - INTERACT_CONTAINER
    - INTERACT_MECHANISM
    - INTERACT_VILLAGER
    - BLOCK_IGNITE
    - ATTACK_PLAYER
    - ATTACK_ANIMAL
    - FLY
    - LAND_ENTER
    - SPAWN_TELEPORT
    - VEHICLE_USE
    - ITEM_PICKUP
```

### 动作Flag

> 动作Flag代表玩家执行的动作

+ **BLOCK_PLACE**
  放置方块

+ **BLOCK_BREAK**
  破坏方块
  
+ **INTERACT_GENERAL**
  能够交互其它 `INTERACT_FLAG` 未包括的所有类型

+ **INTERACT_CONTAINER**
  与容器进行交互

+ **INTERACT_VILLAGER**
  与村民交易

+ **BLOCK_IGNITE**
  点燃方块

+ **ATTACK_PLAYER**
  攻击玩家
  如果禁用: *该职位无法攻击任何人.*
  如果启用: *该职位可以攻击其他人,其他人可以在指定的区域中攻击该玩家.*
  注意: *如果在配置中开启了 `COMBAT-TAG` 那么这个Flag可能会失效.*

+ **ATTACK_ANIMAL**
  攻击动物

+ **FLY**
  允许该职位在一个区域内飞行,如果不让玩家在指定的区域内飞行,那么这个Flag将会失效,若他们进入允许飞行的区域内,Lands会重新开启其飞行模式.(如果之前开启过飞行模式)
  每个飞行插件都可以与这个兼容.

+ **LAND_ENTER**
  进入区域

+ **SPAWN_TELEPORT**
  重生点传送

+ **VEHICLE_USAGE**
  允许放置载具

+ **ITEM_PICKUP**
  捡起物品


### 管理Flag

> 管理Flag代表玩家能够编辑Flag以及设置王国

+ **PLAYER_TRUST**
  信任其他玩家

+ **PLAYER_SETROLE**
  为受信任的玩家设置职位(升职或降职)
  *只能编辑优先级比自己低的官职*

+ **PLAYER_UNTRUST**
  取消信任其他玩家
  *只能编辑优先级比自己低的官职*

+ **PLAYER_BAN**
  封禁玩家
  *只能编辑优先级比自己低的官职*

+ **SETTING_EDIT_LAND**
  设置王国自然设置(例如生成怪物等)

+ **SETTING_EDIT_ROLE**
  编辑比自己职位低的官职的职能

+ **SETTING_EDIT_TAXES**
  编辑税收
  注意: *建议将这个Flag设置到你信任的玩家上,而不是一个职位.*
  
## 战争配置

Lands设置有战争系统,能让其它王国与之抗争.此章节仅介绍入门配置,[wars.yml](https://github.com/Iverins/lands/blob/master/Resource/Config/wars.yml)里面带有更详细的说明.

### 战书

若想宣战,请输入 `/wars declare <王国>` .然后,该王国会收到一份详细的战书,例如何时开战以及侵略者设置的战争赔款.如果抵御者投降,那么该笔战争赔款将由抵御者支付.将准备时间设置为 `0` ,可以关闭战书.

1. 最少人数

设置参战的王国的最少受信任的玩家数.

> min-players:
> 设置侵略者最少受信任的玩家数.
> attacker: 0
> 设置抵御者最少受信任的玩家数.
> defender: 0

2. 战前准备

给予抵御者多长时间用来战前准备?

> 注意: 单位为 秒
> 默认为一天
> preparation-time: 1d

3. 战书

宣战是否需要经过双方同意?
如果启用.则在战前,抵御者需要同意这个战书: `/wars declare <侵略者>` 他们可以拒绝迎战: `/wars deny`

> mutual:
> enable_2: false
> 如果敌人在指定的时间内不对战书做出任何回应,是否删除此战书
> 你可以设置为 0 以禁用该选项
> timeout: 5d

### 战争期间

1. 最大战争时长

这是战争的持续时长.

> duration: 36h

2. (官职) 战时FLAG设置

允许玩家在敌国执行以下行为(仅在战时):
行为Flag请参见:
https://github.com/Angeschossen/Lands/wiki/Roles-and-their-Flags#action-flags
注意: 如果将 `BLOCK_PLACE` 或 `BLOCK_BREAK` 添加到此列表中,则侵略者可以破坏/放置所有方块.如果要指定能破坏/放置的方块,请参照下面
> Option: role-settings_list

玩家能够放置在敌国的方块列表:
注意: `role-settings_list` 必须没有  `BLOCK_PLACE` FLAG.
参照: https://hub.spigotmc.org/javadocs/bukkit/org/bukkit/Material.html
> Option: block-place_list

玩家能够在敌国破坏的方块列表:
注意: `role-settings_list` 必须没有  `BLOCK_BREAK` FLAG.
参照: https://hub.spigotmc.org/javadocs/bukkit/org/bukkit/Material.html
> Option: block-break_list

# 权限

## 数字类

**请将 x 替换为数字**

`lands.lands.x`
描述: 玩家可以成为多少个王国的国民
**注意:** 这不包括自己的王国.

`lands.ownlands.x`
描述: 玩家可以成为多少个王国的国王

`lands.chunks.x`
描述: 玩家在每个王国内可以占领多少个区块

`lands.chunks.support.x`
描述: 玩家可以为自己的王国上供多少区块

`lands.members.x`
描述: 每个王国可以有多少个国民

`lands.areas.x`
描述: 每个王国可以有多少个区域

`lands.roles.x`
描述: 每个王国可以有多少位官员

`lands.free.chunks.x`
描述: 设置可占领区块

`lands.free.land.x`
描述: 设置可创建王国的数量

`lands.selection.x`
描述: 可用 `/lands selection` 设置的最大区块数量

## 命令类

请参见: **入门 -> 命令**

## 玩家奖励类

只有开启了 **玩家时间奖励** 选项才需要

```yaml

```




