---
author: ['Nguyễn Đức Chiến']
date: 1633348853
title: "sshd, TLDR Pages"
description: "sshd, Secure Shell Daemon - allows remote machines to securely log in to the current machine."
categories: "common"
---
> Remote machines can execute commands as it is executed at this machine.

> More information: <https://man.openbsd.org/sshd>.

- Start daemon in the background:

```bash
sshd
```

- Run sshd in the foreground:

```bash
sshd -D
```

- Run with verbose output (for debugging):

```bash
sshd -D -d
```

- Run on a specific port:

```bash
sshd -p port
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Nguyễn Đức Chiến](mailto:nobi@nobidev.com) | sshd: add page (#6610) | 2021-10-04T14:00:53 | [8facf8e18af6](https://github.com/tldr-pages/tldr/commit/8facf8e18af6fe7fdff340541fc4c26bda53b0a5)

