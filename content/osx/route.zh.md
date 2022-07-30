---
author: ['bl-ue', 'marchersimon', 'Ein Verne', 'wizarot']
date: 1659075216
title: "route, TLDR Pages"
description: "route, 手动操作路由表。"
categories: "osx"
---
> 需要 root 权限。

> 更多信息：<https://www.manpagez.com/man/8/route/>.

- 通过网关向目标添加路由：

```bash
sudo route add 路由 ip 地址 网关地址
```

- 通过网关向 子网 / 24 添加路由：

```bash
sudo route add 子网 ip/24 网关地址
```

- 在测试模式下运行（不做任何操作，只打印）：

```bash
sudo route -t add 路由 ip 地址/24 网关地址
```

- 删除所有路由：

```bash
sudo route flush
```

- 删除特定路由：

```bash
sudo route delete 路由 ip 地址/24
```

- 查找并显示目标的路由（主机名或 IP 地址）：

```bash
sudo route get 目标
```
对该文件所做的修改清单


作者 | 描述 | ISO 8601日期格式 | 链接到GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | Sync more information links with all translations (#8256) | 2022-07-29T08:13:36 | [1f610a952ea0](https://github.com/tldr-pages/tldr/commit/1f610a952ea0d53e0a1bdbd1246ef81f24db2f3f)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | Chinese pages: correct Chinese punctuation (#5240) | 2021-08-02T10:41:09 | [289e30dfb3d1](https://github.com/tldr-pages/tldr/commit/289e30dfb3d1d73bade9e3610e12bfc90e9270ae)
[Ein Verne](mailto:einverne@gmail.com) | format translation: update | 2019-11-02T18:47:23 | [b33795f8ab11](https://github.com/tldr-pages/tldr/commit/b33795f8ab11d9b0b539e149d5f450af7a059b3a)
[wizarot](mailto:wizarot@qq.com) | route: add Chinese translation | 2019-03-15T12:47:29 | [1eeb988e0bd3](https://github.com/tldr-pages/tldr/commit/1eeb988e0bd3957d6bdc81bccfbc2e3ef9946dba)

