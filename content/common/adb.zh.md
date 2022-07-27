---
author: ['marchersimon', 'bl-ue', 'Starccy', 'Ein Verne', 'Seth Falco', 'zhouquan']
date: 1648358715
title: "adb, TLDR Pages"
description: "adb, 安卓调试桥：与 Android 模拟器或已连接的 Android 设备通信。"
categories: "common"
---
> 此命令也有关于其子命令的文件，例如：`adb shell`.

> 更多信息：<https://developer.android.com/studio/command-line/adb>.

- 检查 adb server 进程的是否在运行，并开启它：

```bash
adb start-server
```

- 终止 adb server 进程：

```bash
adb kill-server
```

- 在目标模拟器 / 设备实例上开启一个远程 shell：

```bash
adb shell
```

- 将 Android 应用程序推送到模拟器 / 设备：

```bash
adb install -r 路径/到/应用.apk
```

- 从目标设备上拷贝一个文件 / 目录到本地：

```bash
adb pull 路径/到/设备的文件或目录 路径/到/本地上的目录
```

- 从本地拷贝一个文件 / 目录到目标设备：

```bash
adb push 路径/到/本地文件或目录 路径/到/设备上的目录
```

- 列出已连接的设备：

```bash
adb devices
```
对该文件所做的修改清单


作者 | 描述 | ISO 8601日期格式 | 链接到GitHub
------|-----|-----|-----
[Seth Falco](mailto:seth@falco.fun) | *: normalize colons (#7913) | 2022-03-27T07:25:15 | [27ff55fc2eea](https://github.com/tldr-pages/tldr/commit/27ff55fc2eea445eb5216c3b1d934960539fc024)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | mention subcommands in every base page (#6383) | 2021-09-13T10:21:21 | [bd677b8b4826](https://github.com/tldr-pages/tldr/commit/bd677b8b48260e301fb99fea794f4dc1458d1562)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | Chinese pages: remove space in More info link (#6305) | 2021-08-31T09:13:49 | [c70c0c26884e](https://github.com/tldr-pages/tldr/commit/c70c0c26884ee74fabb640cd842d1e4c72d9df4b)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | Chinese pages: correct Chinese punctuation (#5240) | 2021-08-02T10:41:09 | [289e30dfb3d1](https://github.com/tldr-pages/tldr/commit/289e30dfb3d1d73bade9e3610e12bfc90e9270ae)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | multiple pages: normalize "more information" labels (#5140) | 2021-01-15T18:24:49 | [c59f12aa9f55](https://github.com/tldr-pages/tldr/commit/c59f12aa9f55d85612ba22e4da86db293ff76977)
[zhouquan](mailto:748583403@qq.com) | aapt to buku: add Chinese translation (#4846) | 2020-11-04T21:12:56 | [8f73cca2e7aa](https://github.com/tldr-pages/tldr/commit/8f73cca2e7aac9b8ef6d721d2083d64ed9879d1c)
[Ein Verne](mailto:einverne@gmail.com) | format translation: change colon | 2019-11-02T18:47:23 | [30c2bd4c7ca2](https://github.com/tldr-pages/tldr/commit/30c2bd4c7ca2385e09cc00f15ad651e195b82e65)
[Ein Verne](mailto:einverne@gmail.com) | format translation: change period | 2019-11-02T18:47:23 | [f0f2764de273](https://github.com/tldr-pages/tldr/commit/f0f2764de2737f4c7bc75feeec5499117dea6ed0)
[Ein Verne](mailto:einverne@gmail.com) | format zh translations | 2019-11-02T18:47:23 | [7f995941edad](https://github.com/tldr-pages/tldr/commit/7f995941edaddaa6bd3208856ec539f5439f7ef4)
[Starccy](mailto:452276725@qq.com) | adb: add Chinese translation | 2019-04-17T21:44:55 | [7881a5c00c88](https://github.com/tldr-pages/tldr/commit/7881a5c00c889abe824c41b17506854cdeb74012)
[Starccy](mailto:452276725@qq.com) | adb: add Chinese translation | 2019-04-17T21:44:55 | [0ac71532fa4c](https://github.com/tldr-pages/tldr/commit/0ac71532fa4c3a9da612de24c2e84ac7682be8eb)

