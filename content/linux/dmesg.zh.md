---
author: ['Stig124', 'xiaolong', 'marchersimon']
date: 1630394029
title: "dmesg"
description: "dmesg, 显示或控制内核环形缓冲区。"
categories: "linux"
---
> 更多信息：<https://manned.org/dmesg>.

- 显示来自内核环形缓冲区的所有消息：

```bash
dmesg
```

- 只显示严重错误级别的消息：

```bash
dmesg --level err
```

- 等待新消息。仅在具有可读性的系统上支持此功能，类似于 `tail -f`（从内核 3.5.0 版本开始）：

```bash
dmesg -w
```

- 显示此系统上有多少物理内存可用：

```bash
dmesg | grep -i memory
```

- 以分页方式显示内核缓冲区的所有消息：

```bash
dmesg | less
```

- 打印人类可读的时间戳（从内核 3.5.0 版本开始）：

```bash
dmesg -T
```

- 启用人类可读的输出：

```bash
dmesg -H
```

- 着色输出：

```bash
dmesg -L
```
对该文件所做的修改清单


作者 | 描述 | ISO 8601日期格式 | 链接到GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | Chinese pages: remove space in More info link (#6305) | 2021-08-31T09:13:49 | [c70c0c26884e](https://github.com/tldr-pages/tldr/commit/c70c0c26884ee74fabb640cd842d1e4c72d9df4b)
[Stig124](mailto:stigpro@outlook.fr) | linux/[a-g]: add more information link (#6076) | 2021-07-09T16:45:55 | [3697c62b5e5c](https://github.com/tldr-pages/tldr/commit/3697c62b5e5cd9bae7a99c591cb81d1ddcfbf792)
[xiaolong](mailto:65013593+xiaolong-666@users.noreply.github.com) | dmesg: add Chinese translation (#5954) | 2021-05-14T20:06:12 | [f2cf84ec2926](https://github.com/tldr-pages/tldr/commit/f2cf84ec2926f4c3023089ac946af97fa9513d82)

