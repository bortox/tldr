---
author: ['Owen Voke']
date: 1572455061
title: "rpcinfo, TLDR Pages"
description: "rpcinfo, List programs via RPC on remote computers."
categories: "windows"
---
> More information: <https://docs.microsoft.com/windows-server/administration/windows-commands/rpcinfo>.

- List all programs registered on the local computer:

```bash
rpcinfo
```

- List all programs registered on a remote computer:

```bash
rpcinfo /p computer_name
```

- Call a specific program on a remote computer using TCP:

```bash
rpcinfo /t computer_name program_name
```

- Call a specific program on a remote computer using UDP:

```bash
rpcinfo /u computer_name program_name
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Owen Voke](mailto:owzie123@gmail.com) | rpcinfo: add page (#3475) | 2019-10-30T18:04:21 | [64b12cbabcd7](https://github.com/tldr-pages/tldr/commit/64b12cbabcd700dbe1000ef6f34eda6ebe225fdb)

