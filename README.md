# anApp-ip-forward
简单的ip转发程序，目前只支持window, linux 可以自己通过源码修改

源码git, ip-forward 分支
https://github.com/hellokeke123/anApp.git

有效配置如下
```
title = "ipForwardSimple"

[app]
context= "client"

[contextClient]
TunIp="10.0.2.1"     # tun 网卡ip  10.0.2.1/24
SourceIp="192.168.0.2"    # 访问 192.168.0.2  指向  192.168.0.25
TargetIp="192.168.0.25"
```

2025-05-13更新v0.2：
移除无效功能