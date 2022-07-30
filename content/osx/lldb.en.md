---
author: ['Waldir Pimenta', 'Gear J', 'Emily Grace Seville', 'Kevin Ushey']
date: 1644837703
title: "lldb"
description: "lldb, The LLVM Low-Level Debugger."
categories: "osx"
---
> More information: <https://lldb.llvm.org/man/lldb.html>.

- Debug an executable:

```bash
lldb "executable"
```

- Attach `lldb` to a running process with a given PID:

```bash
lldb -p pid
```

- Wait for a new process to launch with a given name, and attach to it:

```bash
lldb -w -n "process_name"
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Emily Grace Seville](mailto:emilyseville7cf@gmail.com) | osx/*: update page (#7665) | 2022-02-14T12:21:43 | [692469016e62](https://github.com/tldr-pages/tldr/commit/692469016e62d4410ec92a8f29272e447046a0d2)
[Gear J](mailto:12108619+gearj@users.noreply.github.com) | launchctl, lldb, locate, look: add more information link (#6893) | 2021-10-11T07:08:25 | [fcc03f1e6ff9](https://github.com/tldr-pages/tldr/commit/fcc03f1e6ff9776ca4433447e9859a3c1a42e539)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | lldb: remove token markup in example description | 2017-09-05T01:01:28 | [90a1dd4f1755](https://github.com/tldr-pages/tldr/commit/90a1dd4f17551074d14cd26a7ba06422d38384d4)
[Kevin Ushey](mailto:kevinushey@gmail.com) | lldb.md: add page (#1444) | 2017-08-14T17:11:57 | [718f4bb0b8a1](https://github.com/tldr-pages/tldr/commit/718f4bb0b8a1bd2cf32dd0c6ce8d05643ad58ab1)

