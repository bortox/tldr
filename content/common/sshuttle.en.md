---
author: ['marchersimon', 'syleung']
date: 1633351190
title: "sshuttle, TLDR Pages"
description: "sshuttle, Transparent proxy server that tunnels traffic over an SSH connection."
categories: "common"
---
> Doesn't require root or any special setup on the remote SSH server, though root access on the local machine is prompted for.

> More information: <https://manned.org/sshuttle>.

- Forward all IPv4 TCP traffic via a remote SSH server:

```bash
sshuttle --remote=username@sshserver 0.0.0.0/0
```

- Also forward all DNS traffic to the server's default DNS resolver:

```bash
sshuttle --dns --remote=username@sshserver 0.0.0.0/0
```

- Forward all traffic except that which is bound for a specific subnet:

```bash
sshuttle --remote=username@sshserver 0.0.0.0/0 --exclude 192.168.0.1/24
```

- Use the tproxy method to forward all IPv4 and IPv6 traffic:

```bash
sshuttle --method=tproxy --remote=username@sshserver 0.0.0.0/0 ::/0 --exclude=your_local_ip_address --exclude=ssh_server_ip_address
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[syleung](mailto:syleung@users.noreply.github.com) | common/ssh*: add more information link (#6659) | 2021-10-04T14:39:50 | [a092be52d7de](https://github.com/tldr-pages/tldr/commit/a092be52d7ded26ec56154160c90900c6338e76d)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | pwgen, sshuttle, trap, tree: move to common (#6551) | 2021-09-19T16:13:40 | [6474a3284244](https://github.com/tldr-pages/tldr/commit/6474a3284244a623c5ba32264a99d6a27a3bcce3)

