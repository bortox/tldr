---
author: ['zhouquan', 'bl-ue', 'marchersimon']
date: 1630394029
title: "adb shell, TLDR Pages"
description: "adb shell, 安卓调试桥-Shell: 运行安卓模拟器或者连接设备上的远程终端命令。"
categories: "common"
---
> 更多信息：<https://developer.android.com/studio/command-line/adb>.

- 启动模拟器/设备上的远程终端：

```bash
adb shell
```

- 获取模拟器/设备全部属性：

```bash
adb shell getprop
```

- 重置所有运行时权限为它们的默认值：

```bash
adb shell pm reset-permissions
```

- 撤销一个应用的危险权限：

```bash
adb shell pm revoke 包名 权限
```

- 触发一个键盘敲击事件：

```bash
adb shell input keyevent 键位码
```

- 清除模拟器/设备上的数据：

```bash
adb shell pm clear 包名
```

- 启动模拟器/设备上的一个行为：

```bash
adb shell am start -n 包名/活动名
```

- 启动模拟器/设备上的首页活动：

```bash
adb shell am start -W -c android.intent.category.HOME -a android.intent.action.MAIN
```
对该文件所做的修改清单


作者 | 描述 | ISO 8601日期格式 | 链接到GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | Chinese pages: remove space in More info link (#6305) | 2021-08-31T09:13:49 | [c70c0c26884e](https://github.com/tldr-pages/tldr/commit/c70c0c26884ee74fabb640cd842d1e4c72d9df4b)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | Chinese pages: correct Chinese punctuation (#5240) | 2021-08-02T10:41:09 | [289e30dfb3d1](https://github.com/tldr-pages/tldr/commit/289e30dfb3d1d73bade9e3610e12bfc90e9270ae)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | *: clean up token syntax delimiters (#5677) | 2021-04-04T02:08:57 | [289787c7e8c1](https://github.com/tldr-pages/tldr/commit/289787c7e8c1177742d23004198253154fe50c3c)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | Chinese pages: fix (valid) tldr-lint errors (#5375) | 2021-03-08T21:22:42 | [7b57b87145b6](https://github.com/tldr-pages/tldr/commit/7b57b87145b67f1642251659b3568739f963754f)
[zhouquan](mailto:748583403@qq.com) | aapt to buku: add Chinese translation (#4846) | 2020-11-04T21:12:56 | [8f73cca2e7aa](https://github.com/tldr-pages/tldr/commit/8f73cca2e7aac9b8ef6d721d2083d64ed9879d1c)

