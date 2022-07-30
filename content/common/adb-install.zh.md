---
author: ['bl-ue', 'zhouquan', 'Seth Falco', 'marchersimon']
date: 1648358715
title: "adb install"
description: "adb install, 安卓调试桥 -Install: 将应用安装包推送到 Android 模拟器或已连接的安卓设备。"
categories: "common"
---
> 更多信息：<https://developer.android.com/studio/command-line/adb>.

- 向模拟器/设备推送安卓 app：

```bash
adb install 路径/到/应用.apk
```

- 重装 app, 保持原有数据：

```bash
adb install -r 路径/到/应用.apk
```

- 授予 app manifest 中列举的所有权限许可：

```bash
adb install -g 路径/到/应用.apk
```

- 快速部署模式，仅更新 APK 更改过的部分：

```bash
adb install --fastdeploy 路径/到/应用.apk
```
对该文件所做的修改清单


作者 | 描述 | ISO 8601日期格式 | 链接到GitHub
------|-----|-----|-----
[Seth Falco](mailto:seth@falco.fun) | *: normalize colons (#7913) | 2022-03-27T07:25:15 | [27ff55fc2eea](https://github.com/tldr-pages/tldr/commit/27ff55fc2eea445eb5216c3b1d934960539fc024)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | Chinese pages: remove space in More info link (#6305) | 2021-08-31T09:13:49 | [c70c0c26884e](https://github.com/tldr-pages/tldr/commit/c70c0c26884ee74fabb640cd842d1e4c72d9df4b)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | Chinese pages: correct Chinese punctuation (#5240) | 2021-08-02T10:41:09 | [289e30dfb3d1](https://github.com/tldr-pages/tldr/commit/289e30dfb3d1d73bade9e3610e12bfc90e9270ae)
[zhouquan](mailto:748583403@qq.com) | aapt to buku: add Chinese translation (#4846) | 2020-11-04T21:12:56 | [8f73cca2e7aa](https://github.com/tldr-pages/tldr/commit/8f73cca2e7aac9b8ef6d721d2083d64ed9879d1c)

