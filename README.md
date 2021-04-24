# 项目正在为最新版的McQQBot进行重写工作，如需测试请切换分支至DEV/2.0!
# KitFox
一个基于McQQBot与Skript的Minecraft-QQ机器人。
![吉祥物](https://i.loli.net/2021/04/10/qHizhuI1SVZrPT5.jpg)
# 特点
## 轻量级
KitFox使用Skript插件进行开发，不需要额外进行编译，方便用户安装与修改本体。
## 模块化
KitFox使用模块化设计来更方便地扩展KitFox功能，同时增加程序的稳定性。
## 易上手
KitFox使用类似于一般插件的yaml来存储机器人配置和数据，能让使用者更加快速的配置与使用机器人。
# 安装
1.在安装KitFox前，您需要先安装并配置[Skript](https://www.mcbbs.net/thread-975466-1-1.html)，[McQQBot](https://www.mcbbs.net/forum.php?mod=viewthread&tid=1141509)，[skript-reflect](https://github.com/TPGamesNL/skript-reflect)和[skript-yaml](https://github.com/Sashie/skript-yaml)

2.配置好以上插件后，请将KitFox-CORE.sk放入plugins/Skript/scripts/中并重启服务器

3.重启后打开plugins/KitFox/config.yml进行必要的机器人配置，再次重启
# 扩展
KitFox支持安装各种各样的扩展，请将下载的扩展放入/plugins/Skript/scripts中重启。以下是推荐的扩展：
## KitFox-ChatForwardExtra
### 作者：SinanGentoo
增加了玩家死亡/完成进度/触发掠夺/掠夺胜利等群聊转发
## KitFox-AuthMe
### 作者：SinanGentoo
增加了对AuthMe等登录插件的指令，能够更方便的为玩家注册
## KitFox-Floodgate
### 作者：Zimzaza4
增加了对基岩版玩家在线状态的查询
## KitFox-Maintenance
### 作者：SinanGentoo
增加了一系列方便管理员管理服务器的指令，包括但不限于ban，maintenance，restart等
## KitFox-ServerInfo
### 作者：SinanGentoo
增加了查询服务器状态的命令
