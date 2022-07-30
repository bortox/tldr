---
author: ['Morgan Howard', 'Emily Grace Seville']
date: 1644837703
title: "vpnd"
description: "vpnd, Listens for incoming VPN connections."
categories: "osx"
---
> It should not be invoked manually.

> More information: <https://www.unix.com/man-page/osx/8/vpnd/>.

- Start the daemon:

```bash
vpnd
```

- Run the daemon in the foreground:

```bash
vpnd -x
```

- Run the daemon in the foreground and print logs to the terminal:

```bash
vpnd -d
```

- Run the daemon in the foreground, print logs to the terminal, and quit after validating arguments:

```bash
vpnd -n
```

- Print usage summary and exit:

```bash
vpnd -h
```

- Run the daemon for a specific server configuration:

```bash
vpnd -i server_id
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Emily Grace Seville](mailto:emilyseville7cf@gmail.com) | osx/*: update page (#7665) | 2022-02-14T12:21:43 | [692469016e62](https://github.com/tldr-pages/tldr/commit/692469016e62d4410ec92a8f29272e447046a0d2)
[Morgan Howard](mailto:morganhoward@users.noreply.github.com) | osx/*: add page for macOS interal daemons (#6705) appsleepd auditd avbdevided bird bnepd cfprefsd cloudphotod coreaudiod distnoted [...] | 2021-10-12T05:13:54 | [bb83c2b70569](https://github.com/tldr-pages/tldr/commit/bb83c2b705696df0df9a1b1407baf4df0ebd2ffe)

