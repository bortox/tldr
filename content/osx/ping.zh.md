---
author: ['wizarot', 'bl-ue', 'Ein Verne']
date: 1627893669
title: "ping, TLDR Pages"
description: "ping, 向网络主机发送 ICMP 回显请求数据包。"
categories: "osx"
---
- Ping 指定的主机：

```bash
ping 主机
```

- 对主机执行指定定次数的 ping 操作：

```bash
ping -c 次数 主机
```

- ping `主机` , 指定请求之间的间隔（以`秒`为单位）（默认为 1 秒）：

```bash
ping -i 秒 主机
```

- Ping `主机`, 但不尝试查找地址的符号名：

```bash
ping -n 主机
```

- ping `主机` 并在收到数据包时响铃（如果您的终端支持）：

```bash
ping -a 主机
```

- ping `主机` 并打印接收数据包的时间（此选项是 Apple 的附加项）：

```bash
ping --apple-time 主机
```
对该文件所做的修改清单


作者 | 描述 | ISO 8601日期格式 | 链接到GitHub
------|-----|-----|-----
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | Chinese pages: correct Chinese punctuation (#5240) | 2021-08-02T10:41:09 | [289e30dfb3d1](https://github.com/tldr-pages/tldr/commit/289e30dfb3d1d73bade9e3610e12bfc90e9270ae)
[Ein Verne](mailto:einverne@gmail.com) | format translation: update | 2019-11-02T18:47:23 | [b33795f8ab11](https://github.com/tldr-pages/tldr/commit/b33795f8ab11d9b0b539e149d5f450af7a059b3a)
[wizarot](mailto:wizarot@qq.com) | ping: add Chinese translation | 2019-03-15T12:47:29 | [0e91797ef63e](https://github.com/tldr-pages/tldr/commit/0e91797ef63e5a6fbc565384cea66f7fabf28acc)

