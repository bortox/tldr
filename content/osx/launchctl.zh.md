---
author: ['bl-ue', 'wizarot', 'Ein Verne', 'Gear J', 'Seth Falco']
date: 1648358715
title: "launchctl, TLDR Pages"
description: "launchctl, 用于启动守护程序（系统范围的服务）和启动代理程序（每个用户程序）的命令行界面，该界面指向苹果的`launchd` 管理工具。"
categories: "osx"
---
> `launchd`加载放置在适当位置的基于 XML 的`*.plist`文件，并根据其定义的计划运行相应的命令。

> 更多信息：<https://manned.org/launchctl>.

- 每当用户登录时，自动将 plist 文件加载到 `launchd`：

```bash
launchctl load ~/Library/LaunchAgents/我的脚本.plist
```

- 激活需要 root 权限才能运行和 / 或在任何用户登录时都应加载的脚本（注意路径中不能有`~`）：

```bash
sudo launchctl load /Library/LaunchAgents/root 脚本.plist
```

- 激活一个系统范围的守护程序，以便在系统启动时加载（即使没有用户登录也会加载）：

```bash
sudo launchctl load /Library/LaunchDaemons/系统脚本.plist
```

- 显示所有加载的代理 / 守护进程，如果它们指定的进程当前正在运行，则显示 pid，如果停止那么返回了它们上次运行的时间和退出代码：

```bash
launchctl list
```

- 卸载当前加载的脚本，例如进行更改（注意：重新启动和 / 或登录后，plist 文件将自动加载到`launchd`）：

```bash
launchctl unload ~/Library/LaunchAgents/我的脚本.plist
```

- 手动运行一个已知的（已加载的）脚本 / 守护进程，即使它不是正确的时间（注意：此命令使用脚本的标签，而不是文件名）：

```bash
launchctl start 我的脚本
```

- 手动终止与已知脚本 / 守护进程关联的进程（如果该进程正在运行）：

```bash
launchctl stop 我的脚本
```
对该文件所做的修改清单


作者 | 描述 | ISO 8601日期格式 | 链接到GitHub
------|-----|-----|-----
[Seth Falco](mailto:seth@falco.fun) | *: normalize colons (#7913) | 2022-03-27T07:25:15 | [27ff55fc2eea](https://github.com/tldr-pages/tldr/commit/27ff55fc2eea445eb5216c3b1d934960539fc024)
[Gear J](mailto:12108619+gearj@users.noreply.github.com) | launchctl, lldb, locate, look: add more information link (#6893) | 2021-10-11T07:08:25 | [fcc03f1e6ff9](https://github.com/tldr-pages/tldr/commit/fcc03f1e6ff9776ca4433447e9859a3c1a42e539)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | Chinese pages: correct Chinese punctuation (#5240) | 2021-08-02T10:41:09 | [289e30dfb3d1](https://github.com/tldr-pages/tldr/commit/289e30dfb3d1d73bade9e3610e12bfc90e9270ae)
[Ein Verne](mailto:einverne@gmail.com) | format translation: change colon | 2019-11-02T18:47:23 | [30c2bd4c7ca2](https://github.com/tldr-pages/tldr/commit/30c2bd4c7ca2385e09cc00f15ad651e195b82e65)
[Ein Verne](mailto:einverne@gmail.com) | format translation: change period | 2019-11-02T18:47:23 | [f0f2764de273](https://github.com/tldr-pages/tldr/commit/f0f2764de2737f4c7bc75feeec5499117dea6ed0)
[Ein Verne](mailto:einverne@gmail.com) | format zh translations | 2019-11-02T18:47:23 | [7f995941edad](https://github.com/tldr-pages/tldr/commit/7f995941edaddaa6bd3208856ec539f5439f7ef4)
[wizarot](mailto:wizarot@qq.com) | launchctl: add Chinses translation | 2019-03-05T09:15:04 | [69cc1fc7ba70](https://github.com/tldr-pages/tldr/commit/69cc1fc7ba70465fbeabad6215e083ddc2a179fe)

