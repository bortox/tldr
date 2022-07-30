---
author: ['pixel', 'Emily Grace Seville']
date: 1644837703
title: "sntpd"
description: "sntpd, An SNTP server."
categories: "osx"
---
> It should not be invoked manually.

> More information: <https://linux.die.net/man/8/snmpd>.

- Start the daemon:

```bash
sntpd
```

- Overwrite existing state with the local clock (stratum 1), for running a master/primary server, without synchronizing with another (higher stratum) server:

```bash
sntpd -L
```

- Use a custom file for the SNTP state:

```bash
sntpd -z path/to/state.bin
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Emily Grace Seville](mailto:emilyseville7cf@gmail.com) | osx/*: update page (#7665) | 2022-02-14T12:21:43 | [692469016e62](https://github.com/tldr-pages/tldr/commit/692469016e62d4410ec92a8f29272e447046a0d2)
[pixel](mailto:chrissx@chrissx.de) | applecamerad, sntpd: add page (#7005) | 2021-10-17T22:00:28 | [e2e34c5bd1fe](https://github.com/tldr-pages/tldr/commit/e2e34c5bd1fec00c1b2eb38d3fb654712cbecc0d)

