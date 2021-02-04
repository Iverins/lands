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

![AreaItem](E:\MCBBS Translate\Lands\Lands\Resource\AreaItem.png)

2. 现在点击进去,然后点击创建区域,并且在聊天框输入区域名字.

![AreaCreate](E:\MCBBS Translate\Lands\Lands\Resource\AreaCreate.png)

3. 之后，你会发现你打开了区域菜单，并且告诉你如何设置区域大小.

![AreaSize](E:\MCBBS Translate\Lands\Lands\Resource\AreaSize.png)

4. 当设置完毕后,它会实时显示区域大小给你,你可以根据你的需要进行更改,然后只需要再次输入 `/lands selection` 既可.

![AreaSelection](E:\MCBBS Translate\Lands\Lands\Resource\SelectionSuccessful.png)

### 信任玩家&设置Flags

请再次打开区域菜单,你可以在这片区域信任一个玩家,或者编辑其它玩家能用的权限(类似于 Residence 的领地权限一般,称之为 Flags[标志]),而且,你可以为这片区域当成一个小王国.

![Flags](E:\MCBBS Translate\Lands\Lands\Resource\Flags.png)



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

![RentSign](E:\MCBBS Translate\Lands\Lands\Resource\RentSign.jpg)

#### 说明

+ 以上例子:
  + 花费 **$200** 能租借 **5** 天. 
  + 最大可租借天数为 **50** 天.
+ 牌子可以使用: **d = 天** | **h = 小时** | **m = 分钟**
  + 如果没有写上,默认用 **d**
+ 你只能租出一片区域,对于卖出,默认是卖出一片区域(或者是卖出一整个王国,以下有说明)

#### 设置以后

![Result](E:\MCBBS Translate\Lands\Lands\Resource\Result.jpg)

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

![SellSign](E:\MCBBS Translate\Lands\Lands\Resource\SellSign.jpg)

#### 说明

+ 以上例子:
  + 花费 **$5000** 来买下整片区域.
  + 而后那个玩家将会成为那片区域的主人

#### 设置以后

![ResultSign](E:\MCBBS Translate\Lands\Lands\Resource\ResultSell.jpg)

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

## 配置

### 常见配置问题

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
**答:** 