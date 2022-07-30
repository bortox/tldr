---
author: ['Ein Verne', 'wizarot', 'bl-ue', 'meowmeowcat']
date: 1635945242
title: "pmset"
description: "pmset, 配置 macOS 电源管理设置，就像在系统首选项 > 节能程序中一样。"
categories: "osx"
---
> 修改设置的命令必须以 `sudo` 开头。

> 更多信息：<https://ss64.com/osx/pmset.html>.

- 显示当前电源管理设置：

```bash
pmset -g
```

- 显示当前电源和电池电量：

```bash
pmset -g batt
```

- 立即让显示器进入休眠状态：

```bash
pmset displaysleepnow
```

- 当充电器通电时，将显示器设置为从不休眠：

```bash
sudo pmset -c displaysleep 0
```

- 使用电池电源 15 分钟后将显示器设置为休眠：

```bash
sudo pmset -b displaysleep 15
```

- 安排计算机在每个工作日上午 9 点自动唤醒：

```bash
sudo pmset repeat wake MTWRF 09:00:00
```

- 还原为系统默认值：

```bash
sudo pmset -a displaysleep 10 disksleep 10 sleep 30 womp 1
```
对该文件所做的修改清单


作者 | 描述 | ISO 8601日期格式 | 链接到GitHub
------|-----|-----|-----
[meowmeowcat](mailto:meowmeowcat1211@gmail.com) | pmset: update Chinese translation (#7335) | 2021-11-03T14:14:02 | [db9a54cf8aca](https://github.com/tldr-pages/tldr/commit/db9a54cf8acab82447f09ebca379429d794b7bea)
[meowmeowcat](mailto:meowmeowcat1211@gmail.com) | osascript, xattr, pmset, say, screencapture: add link (#7368) | 2021-11-02T14:02:04 | [b85bc433fb19](https://github.com/tldr-pages/tldr/commit/b85bc433fb1916e6fd9b053f9db24284d11fc4e6)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | Chinese pages: correct Chinese punctuation (#5240) | 2021-08-02T10:41:09 | [289e30dfb3d1](https://github.com/tldr-pages/tldr/commit/289e30dfb3d1d73bade9e3610e12bfc90e9270ae)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | *: fix typos reported by Hunspell (#5848) Co-authored-by: marchersimon <50295997+marchersimon@users.noreply.github.com> Co-authored- [...] | 2021-05-20T22:13:41 | [8ebd171d6f00](https://github.com/tldr-pages/tldr/commit/8ebd171d6f001698709fefc02b1fd5cc9f3a99c4)
[Ein Verne](mailto:einverne@gmail.com) | format translation: update | 2019-11-02T18:47:23 | [b33795f8ab11](https://github.com/tldr-pages/tldr/commit/b33795f8ab11d9b0b539e149d5f450af7a059b3a)
[Ein Verne](mailto:einverne@gmail.com) | format translation: change period | 2019-11-02T18:47:23 | [f0f2764de273](https://github.com/tldr-pages/tldr/commit/f0f2764de2737f4c7bc75feeec5499117dea6ed0)
[wizarot](mailto:wizarot@qq.com) | pmset: add Chinese translation | 2019-03-15T12:47:29 | [b73c42a50adf](https://github.com/tldr-pages/tldr/commit/b73c42a50adf8b0313c3bc7f75488649f0e8edce)

