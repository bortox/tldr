---
author: ['Seth Falco', 'bl-ue', 'Ein Verne', 'marchersimon', 'wizarot', 'Guido Lena Cota']
date: 1659075216
title: "networksetup, TLDR Pages"
description: "networksetup, 网络系统首选项配置工具。"
categories: "osx"
---
> 更多信息：<https://support.apple.com/guide/remote-desktop/about-networksetup-apdd0c5a2d5/mac>.

- 列出可用的网络服务源（以太网、Wi-Fi、蓝牙等）：

```bash
networksetup -listallnetworkservices
```

- 显示特定网络设备的配置信息：

```bash
networksetup -getinfo "Wi-Fi"
```

- 获取当前连接的 Wi-Fi 网络名称（Wi-Fi 设备通常为 en0 或 en1）：

```bash
networksetup -getairportnetwork en0
```

- 连接到给定的 Wi-Fi 网络 Connect to a particular Wi-Fi network：

```bash
networksetup -setairportnetwork en0 "无线网 SSID" 密码
```
对该文件所做的修改清单


作者 | 描述 | ISO 8601日期格式 | 链接到GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | Sync more information links with all translations (#8256) | 2022-07-29T08:13:36 | [1f610a952ea0](https://github.com/tldr-pages/tldr/commit/1f610a952ea0d53e0a1bdbd1246ef81f24db2f3f)
[Seth Falco](mailto:seth@falco.fun) | *: normalize colons (#7913) | 2022-03-27T07:25:15 | [27ff55fc2eea](https://github.com/tldr-pages/tldr/commit/27ff55fc2eea445eb5216c3b1d934960539fc024)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | Chinese pages: correct Chinese punctuation (#5240) | 2021-08-02T10:41:09 | [289e30dfb3d1](https://github.com/tldr-pages/tldr/commit/289e30dfb3d1d73bade9e3610e12bfc90e9270ae)
[Guido Lena Cota](mailto:guido.lenacota@kreuzwerker.de) | Bulk change: move double quotes outside tokens (#4431) | 2020-10-04T19:33:38 | [354d4b8748ee](https://github.com/tldr-pages/tldr/commit/354d4b8748ee58813dd6830ced7c3b11067255d7)
[Ein Verne](mailto:einverne@gmail.com) | format translation: update | 2019-11-02T18:47:23 | [b33795f8ab11](https://github.com/tldr-pages/tldr/commit/b33795f8ab11d9b0b539e149d5f450af7a059b3a)
[wizarot](mailto:wizarot@qq.com) | networksetup: add Chinese translation | 2019-03-15T12:47:29 | [43a77f0674a1](https://github.com/tldr-pages/tldr/commit/43a77f0674a1ab9851ac3891068c912fb1c7cf75)

