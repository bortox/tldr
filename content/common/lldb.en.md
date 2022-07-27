---
author: ['bl-ue']
date: 1617131024
title: "lldb, TLDR Pages"
description: "lldb, The LLVM Low-Level Debugger."
categories: "common"
---
> More information: <https://lldb.llvm.org>.

- Debug an executable:

```bash
lldb executable
```

- Attach `lldb` to a running process with a given PID:

```bash
lldb -p pid
```

- Wait for a new process to launch with a given name, and attach to it:

```bash
lldb -w -n process_name
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | lldb: move from linux/ to common/, add more info link (#5643) | 2021-03-30T21:03:44 | [8ac9a53478df](https://github.com/tldr-pages/tldr/commit/8ac9a53478dfb1dce5e551be32747b95eb447ef8)

