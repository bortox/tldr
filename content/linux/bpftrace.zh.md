---
author: ['千玄子']
date: 1630035519
title: "bpftrace"
description: "bpftrace, Linux eBPF 的高级跟踪语言。"
categories: "linux"
---
> 更多信息：<https://github.com/iovisor/bpftrace>.

- 显示 bpftrace 版本：

```bash
bpftrace -V
```

- 列出所有可用的探针：

```bash
sudo bpftrace -l
```

- 运行单行程序（例如按程序进行系统调用计数）：

```bash
sudo bpftrace -e 'tracepoint:raw_syscalls:sys_enter { @[comm] = count(); }'
```

- 从文件运行程序：

```bash
sudo bpftrace 文件
```

- 通过 PID 跟踪程序：

```bash
sudo bpftrace -e 'tracepoint:raw_syscalls:sys_enter /pid == 123/ { @[comm] = count(); }'
```

- 进行试运行并以 eBPF 格式显示输出：

```bash
sudo bpftrace -d -e '单行程序'
```
对该文件所做的修改清单


作者 | 描述 | ISO 8601日期格式 | 链接到GitHub
------|-----|-----|-----
[千玄子](mailto:ownbyzjuyk@gmail.com) | aurvote, b*: add Chinese translation (#6413) * aurvote: add Chinese translation * balooctl: add Chinese translation * beep: add [...] | 2021-08-27T05:38:39 | [48b9a1350224](https://github.com/tldr-pages/tldr/commit/48b9a1350224488b69961f84ad4d2b93cc85324e)

