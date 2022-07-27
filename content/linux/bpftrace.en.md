---
author: ['André Almeida', 'Seth Falco']
date: 1629050349
title: "bpftrace, TLDR Pages"
description: "bpftrace, High-level tracing language for Linux eBPF."
categories: "linux"
---
> More information: <https://github.com/iovisor/bpftrace>.

- Display bpftrace version:

```bash
bpftrace -V
```

- List all available probes:

```bash
sudo bpftrace -l
```

- Run a one-liner program (e.g. syscall count by program):

```bash
sudo bpftrace -e 'tracepoint:raw_syscalls:sys_enter { @[comm] = count(); }'
```

- Run a program from a file:

```bash
sudo bpftrace path/to/file
```

- Trace a program by PID:

```bash
sudo bpftrace -e 'tracepoint:raw_syscalls:sys_enter /pid == 123/ { @[comm] = count(); }'
```

- Do a dry run and display the output in eBPF format:

```bash
sudo bpftrace -d -e 'one_line_program'
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Seth Falco](mailto:seth@falco.fun) | *: fix errors reported by languagetool (#6069) | 2021-08-15T19:59:09 | [3e4c519004a4](https://github.com/tldr-pages/tldr/commit/3e4c519004a471c861cdc609fd7239ee3355671c)
[André Almeida](mailto:andrealmeid@collabora.com) | bpftrace: add page (#4702) | 2020-10-17T21:47:18 | [83df2f61253a](https://github.com/tldr-pages/tldr/commit/83df2f61253a831bb7b973137431d8a06653e7d8)

