---
author: ['Muhammad Falak R Wani']
date: 1635015396
title: "bpftool"
description: "bpftool, Tool for inspection and simple manipulation of eBPF programs and maps."
categories: "linux"
---
> Some subcommands such as `bpftool prog` have their own usage documentation.

> More information: <https://manned.org/bpftool>.

- List information about loaded `eBPF` programs:

```bash
bpftool prog list
```

- List `eBPF` program attachments in the kernel networking subsystem:

```bash
bpftool net list
```

- List all active links:

```bash
bpftool link list
```

- List all `raw_tracepoint`, `tracepoint`, `kprobe` attachments in the system:

```bash
bpftool perf list
```

- List `BPF Type Format (BTF)` data:

```bash
bpftool btf list
```

- List information about loaded maps:

```bash
bpftool map list
```

- Probe a network device "eth0" for supported `eBPF` features:

```bash
bpftool feature probe dev eth0
```

- Run commands in batch mode from a file:

```bash
bpftool batch file myfile
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Muhammad Falak R Wani](mailto:falakreyaz@gmail.com) | bpftool: add page (#7152) Signed-off-by: Muhammad Falak R Wani <falakreyaz@gmail.com> | 2021-10-23T20:56:36 | [d83441812f7c](https://github.com/tldr-pages/tldr/commit/d83441812f7ca6c05a0b61be856da34e7b37b039)

