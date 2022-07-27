---
author: ['千玄子', 'Axel Navarro']
date: 1643827401
title: "bluetoothctl, TLDR Pages"
description: "bluetoothctl, 从命令行管理蓝牙设备。"
categories: "linux"
---
> 更多信息：<https://bitbucket.org/serkanp/bluetoothctl>.

- 进入 bluetoothctl 外壳程序：

```bash
bluetoothctl
```

- 列出设备：

```bash
bluetoothctl -- devices
```

- 与一个设备配对：

```bash
bluetoothctl -- pair mac 地址
```

- 移除一个设备：

```bash
bluetoothctl -- remove mac 地址
```

- 连接一个已配对的设备：

```bash
bluetoothctl -- connect mac 地址
```

- 断开一个已配对的设备：

```bash
bluetoothctl -- disconnect mac 地址
```
对该文件所做的修改清单


作者 | 描述 | ISO 8601日期格式 | 链接到GitHub
------|-----|-----|-----
[Axel Navarro](mailto:navarroaxel@gmail.com) | *: use author link instead of npm package (#7730) | 2022-02-02T19:43:21 | [c2c16f61acbd](https://github.com/tldr-pages/tldr/commit/c2c16f61acbdca1933961fbbc20a80bdae76ece5)
[千玄子](mailto:ownbyzjuyk@gmail.com) | aurvote, b*: add Chinese translation (#6413) * aurvote: add Chinese translation * balooctl: add Chinese translation * beep: add [...] | 2021-08-27T05:38:39 | [48b9a1350224](https://github.com/tldr-pages/tldr/commit/48b9a1350224488b69961f84ad4d2b93cc85324e)

