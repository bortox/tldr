---
author: ['Emily Grace Seville', 'Nya Meteor']
date: 1644837703
title: "nettop"
description: "nettop, Display updated information about the network."
categories: "osx"
---
> More information: <https://www.manpagez.com/man/1/nettop/>.

- Monitor TCP and UDP sockets from all interfaces:

```bash
nettop
```

- Monitor TCP sockets from Loopback interfaces:

```bash
nettop -m tcp -t loopback
```

- Monitor a specific process:

```bash
nettop -p "process_id|process_name"
```

- Display a per-process summary:

```bash
nettop -P
```

- Print 10 samples of network information:

```bash
nettop -l 10
```

- Monitor changes every 5 seconds:

```bash
nettop -d -s 5
```

- While running nettop, list interactive commands:

```bash
h
```

- Display help:

```bash
nettop -h
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Emily Grace Seville](mailto:emilyseville7cf@gmail.com) | osx/*: update page (#7665) | 2022-02-14T12:21:43 | [692469016e62](https://github.com/tldr-pages/tldr/commit/692469016e62d4410ec92a8f29272e447046a0d2)
[Nya Meteor](mailto:abysslink@outlook.com) | nettop: add page (#6254) | 2021-07-24T18:17:43 | [27dd607f59f0](https://github.com/tldr-pages/tldr/commit/27dd607f59f07146c21828312cec1d613640dc35)

