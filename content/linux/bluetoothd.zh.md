---
author: ['千玄子']
date: 1630035519
title: "bluetoothd"
description: "bluetoothd, 管理蓝牙设备的守护进程。"
categories: "linux"
---
> 更多信息：<https://manned.org/bluetoothd>.

- 启动守护进程：

```bash
bluetoothd
```

- 启动守护进程，日志输出到标准输出：

```bash
bluetoothd --nodetach
```

- 指定一个配置文件启动守护进程（默认是 `/etc/bluetooth/main.conf`）：

```bash
bluetoothd --configfile 配置文件
```

- 启动守护进程并将详细信息输出到标准错误：

```bash
bluetoothd --debug
```

- 使用来自 bluetoothd 或插件源中特定文件启动守护进程并输出详细信息：

```bash
bluetoothd --debug=文件一:文件二:文件三
```
对该文件所做的修改清单


作者 | 描述 | ISO 8601日期格式 | 链接到GitHub
------|-----|-----|-----
[千玄子](mailto:ownbyzjuyk@gmail.com) | aurvote, b*: add Chinese translation (#6413) * aurvote: add Chinese translation * balooctl: add Chinese translation * beep: add [...] | 2021-08-27T05:38:39 | [48b9a1350224](https://github.com/tldr-pages/tldr/commit/48b9a1350224488b69961f84ad4d2b93cc85324e)

