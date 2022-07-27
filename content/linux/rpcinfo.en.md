---
author: ['RH-sdavey', 'Emily Grace Seville']
date: 1647882468
title: "rpcinfo, TLDR Pages"
description: "rpcinfo, Makes an RPC call to an RPC server and reports what it finds."
categories: "linux"
---
> More information: <https://manned.org/rpcinfo>.

- Show full table of all RPC services registered on localhost:

```bash
rpcinfo
```

- Show concise table of all RPC services registered on localhost:

```bash
rpcinfo -s localhost
```

- Display table of statistics of rpcbind operations on localhost:

```bash
rpcinfo -m
```

- Display list of entries of given service name (mountd) and version number (2) on a remote nfs share:

```bash
rpcinfo -l remote_nfs_server_ip mountd 2
```

- Delete the registration for version 1 of the mountd service for all transports:

```bash
rpcinfo -d mountd 1
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Emily Grace Seville](mailto:emilyseville7cf@gmail.com) | linux/*: add more information link (#7848) | 2022-03-21T18:07:48 | [4659bcb243ac](https://github.com/tldr-pages/tldr/commit/4659bcb243ac572c9e0c95117097801f1e62bda4)
[RH-sdavey](mailto:32485509+RH-sdavey@users.noreply.github.com) | rpcinfo: add page (#2295) | 2018-09-07T11:43:24 | [7a703b14d460](https://github.com/tldr-pages/tldr/commit/7a703b14d46005bb41a51c2651e482545a249845)

