---
author: ['Starccy', 'Ein Verne', 'bl-ue', 'marchersimon']
date: 1633112881
title: "cmstp, TLDR Pages"
description: "cmstp, 用于管理连接服务配置文件的命令行工具。"
categories: "windows"
---
> 更多信息：<https://docs.microsoft.com/windows-server/administration/windows-commands/cmstp>.

- 安装指定的配置文件：

```bash
cmstp "配置文件的路径"
```

- 安装时不创建桌面快捷方式：

```bash
cmstp /ns "配置文件的路径"
```

- 安装时不检查依赖：

```bash
cmstp /nf "配置文件的路径"
```

- 仅为当前用户安装：

```bash
cmstp /su "配置文件的路径"
```

- 为所有用户安装（需要管理员权限）：

```bash
cmstp /au "配置文件的路径"
```

- 静默安装：

```bash
cmstp /s "配置文件的路径"
```

- 卸载一个指定的配置文件：

```bash
cmstp /u "配置文件的路径"
```

- 静默删除：

```bash
cmstp /u /s "配置文件的路径"
```
对该文件所做的修改清单


作者 | 描述 | ISO 8601日期格式 | 链接到GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: sync more information links in translations (#6537) | 2021-10-01T20:28:01 | [642dbf2e972e](https://github.com/tldr-pages/tldr/commit/642dbf2e972e388fab8c84ba3b4685fb862b6454)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | Chinese pages: correct Chinese punctuation (#5240) | 2021-08-02T10:41:09 | [289e30dfb3d1](https://github.com/tldr-pages/tldr/commit/289e30dfb3d1d73bade9e3610e12bfc90e9270ae)
[Ein Verne](mailto:einverne@gmail.com) | format translation: change colon | 2019-11-02T18:47:23 | [30c2bd4c7ca2](https://github.com/tldr-pages/tldr/commit/30c2bd4c7ca2385e09cc00f15ad651e195b82e65)
[Ein Verne](mailto:einverne@gmail.com) | format translation: change period | 2019-11-02T18:47:23 | [f0f2764de273](https://github.com/tldr-pages/tldr/commit/f0f2764de2737f4c7bc75feeec5499117dea6ed0)
[Ein Verne](mailto:einverne@gmail.com) | format zh translations | 2019-11-02T18:47:23 | [7f995941edad](https://github.com/tldr-pages/tldr/commit/7f995941edaddaa6bd3208856ec539f5439f7ef4)
[Starccy](mailto:452276725@qq.com) | cmstp: add Chinese translation | 2019-03-12T12:56:23 | [4804a63f18b2](https://github.com/tldr-pages/tldr/commit/4804a63f18b28f0e1e9a30efaaccd53bcdb09d76)

