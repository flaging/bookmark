Tmux
=============
Tmux用途
-------
Tmux是一个将Linux终端中的会话和终端界面分离的一个工具。

应用场景
------
+ 开启多个终端并互相切换
+ 长时间开发以至于需要保存现场
+ 从不同设备进入同一服务器进行开发
+ ...

安装方法
------
见[官方安装文档](https://github.com/tmux/tmux/wiki/Installing)

主要概念
------
+ session ：会话，是指一个完整的连接单位，一个tmux程序可以有多个session
+ windows ：窗口，是指一个占满屏幕的界面，一个session可以有多个windows
+ pane    ：面板，是指一个能输入命令的通道，一个windows可以有多个pane

主要命令
------
| 命令名称 | 命令含义 |
|:------:|:------:|
| tmux new -s name | 建立以name为名字的session |
| tmux detatch | 将session和界面分离 |
| tmux attach -t name | 重新接入name session |
