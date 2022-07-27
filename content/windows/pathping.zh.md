---
author: ['Seth Falco', 'bl-ue', 'Ein Verne', 'Starccy', 'marchersimon']
date: 1648358715
title: "pathping, TLDR Pages"
description: "pathping, 一种结合了`ping`和`tracert`功能的跟踪路由工具。"
categories: "windows"
---
> 更多信息：<https://docs.microsoft.com/windows-server/administration/windows-commands/pathping>.

- Ping 并追踪主机的路由：

```bash
pathping 主机名
```

- 不要对主机名执行 IP 地址的反向查找：

```bash
pathping 主机名 -n
```

- 指定要搜索目标的最大跃点数（默认值为 30）：

```bash
pathping 主机名 -h 最大跃点数
```

- 指定 ping 之间等待的毫秒数（默认值为 240）：

```bash
pathping 主机名 -p 时间
```

- 指定每跳的查询数（默认值为 100）：

```bash
pathping 主机名 -q 查询语句
```

- 强制使用 IPV4：

```bash
pathping 主机名 -4
```

- 强制使用 IPV6：

```bash
pathping 主机名 -6
```

- 显示详细的使用帮助：

```bash
pathping /?
```
对该文件所做的修改清单


作者 | 描述 | ISO 8601日期格式 | 链接到GitHub
------|-----|-----|-----
[Seth Falco](mailto:seth@falco.fun) | *: normalize colons (#7913) | 2022-03-27T07:25:15 | [27ff55fc2eea](https://github.com/tldr-pages/tldr/commit/27ff55fc2eea445eb5216c3b1d934960539fc024)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: sync more information links in translations (#6537) | 2021-10-01T20:28:01 | [642dbf2e972e](https://github.com/tldr-pages/tldr/commit/642dbf2e972e388fab8c84ba3b4685fb862b6454)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | Chinese pages: correct Chinese punctuation (#5240) | 2021-08-02T10:41:09 | [289e30dfb3d1](https://github.com/tldr-pages/tldr/commit/289e30dfb3d1d73bade9e3610e12bfc90e9270ae)
[Ein Verne](mailto:einverne@gmail.com) | format translation: change colon | 2019-11-02T18:47:23 | [30c2bd4c7ca2](https://github.com/tldr-pages/tldr/commit/30c2bd4c7ca2385e09cc00f15ad651e195b82e65)
[Ein Verne](mailto:einverne@gmail.com) | format translation: change period | 2019-11-02T18:47:23 | [f0f2764de273](https://github.com/tldr-pages/tldr/commit/f0f2764de2737f4c7bc75feeec5499117dea6ed0)
[Ein Verne](mailto:einverne@gmail.com) | format zh translations | 2019-11-02T18:47:23 | [7f995941edad](https://github.com/tldr-pages/tldr/commit/7f995941edaddaa6bd3208856ec539f5439f7ef4)
[Starccy](mailto:452276725@qq.com) | pathping: add Chinese translation | 2019-03-12T12:56:23 | [7f319155cc24](https://github.com/tldr-pages/tldr/commit/7f319155cc24d4b19feeb82be1f547093702ac23)

