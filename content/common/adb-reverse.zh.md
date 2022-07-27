---
author: ['zhouquan', 'Seth Falco', 'marchersimon', 'bl-ue']
date: 1648358715
title: "adb reverse, TLDR Pages"
description: "adb reverse, 安卓调试桥-反射： 反向映射安卓模拟器实例或者已连接的实体设备的套接字连接。"
categories: "common"
---
> 更多信息：<https://developer.android.com/studio/command-line/adb>.

- 列出所有来自模拟器和设备的映射连接：

```bash
adb reverse --list
```

- 将 TCP 端口从安卓模拟器或设备中映射到 localhost：

```bash
adb reverse tcp:远程端口 tcp:本地端口
```

- 从安卓模拟器或设备移除一个反向 socket 连接：

```bash
adb reverse --remove tcp:远程端口
```

- 从安卓模拟器或设备移除所有反向 socket 连接：

```bash
adb reverse --remove-all
```
对该文件所做的修改清单


作者 | 描述 | ISO 8601日期格式 | 链接到GitHub
------|-----|-----|-----
[Seth Falco](mailto:seth@falco.fun) | *: normalize colons (#7913) | 2022-03-27T07:25:15 | [27ff55fc2eea](https://github.com/tldr-pages/tldr/commit/27ff55fc2eea445eb5216c3b1d934960539fc024)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | Chinese pages: remove space in More info link (#6305) | 2021-08-31T09:13:49 | [c70c0c26884e](https://github.com/tldr-pages/tldr/commit/c70c0c26884ee74fabb640cd842d1e4c72d9df4b)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | Chinese pages: correct Chinese punctuation (#5240) | 2021-08-02T10:41:09 | [289e30dfb3d1](https://github.com/tldr-pages/tldr/commit/289e30dfb3d1d73bade9e3610e12bfc90e9270ae)
[zhouquan](mailto:748583403@qq.com) | aapt to buku: add Chinese translation (#4846) | 2020-11-04T21:12:56 | [8f73cca2e7aa](https://github.com/tldr-pages/tldr/commit/8f73cca2e7aac9b8ef6d721d2083d64ed9879d1c)

