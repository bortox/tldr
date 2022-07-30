---
author: ['meowmeowcat', 'bl-ue', 'Ein Verne', 'marchersimon', 'wizarot']
date: 1659075216
title: "systemsetup, TLDR Pages"
description: "systemsetup, 配置系统首选项计算机设置。"
categories: "osx"
---
> 更多信息：<https://support.apple.com/guide/remote-desktop/about-systemsetup-apd95406b8d/mac>.

- 启用远程登录（SSH）：

```bash
systemsetup -setremotelogin on
```

- 指定时区、NTP 服务器并启用网络时间：

```bash
systemsetup -settimezone 美国 / 太平洋 -setnetworktimeserver us.pool.ntp.org -setusingnetworktime on
```

- 使机器从不休眠，并在电源故障或内核死机时自动重新启动：

```bash
systemsetup -setsleep off -setrestartpowerfailure on -setrestartfreeze on
```

- disks 选择启动：

```bash
systemsetup -liststartupdisks
```

- 指定新的启动盘：

```bash
systemsetup -setstartupdisk 路径
```
对该文件所做的修改清单


作者 | 描述 | ISO 8601日期格式 | 链接到GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | Sync more information links with all translations (#8256) | 2022-07-29T08:13:36 | [1f610a952ea0](https://github.com/tldr-pages/tldr/commit/1f610a952ea0d53e0a1bdbd1246ef81f24db2f3f)
[meowmeowcat](mailto:meowmeowcat1211@gmail.com) | osx/s*: add link (#7428) | 2021-11-14T20:45:59 | [a36f8550d81b](https://github.com/tldr-pages/tldr/commit/a36f8550d81be6fbe04cb43f3d0a34f30e024b86)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | Chinese pages: correct Chinese punctuation (#5240) | 2021-08-02T10:41:09 | [289e30dfb3d1](https://github.com/tldr-pages/tldr/commit/289e30dfb3d1d73bade9e3610e12bfc90e9270ae)
[Ein Verne](mailto:einverne@gmail.com) | format translation: update | 2019-11-02T18:47:23 | [b33795f8ab11](https://github.com/tldr-pages/tldr/commit/b33795f8ab11d9b0b539e149d5f450af7a059b3a)
[wizarot](mailto:wizarot@qq.com) | systemsetup: add Chinese translation | 2019-03-15T12:47:29 | [be07223d8c7b](https://github.com/tldr-pages/tldr/commit/be07223d8c7b069b026f3db5c656d74a9069b448)

