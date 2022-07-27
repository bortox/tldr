---
author: ['Florian B']
date: 1618858438
title: "bandwhich, TLDR Pages"
description: "bandwhich, Display the current network utilization by process, connection or remote IP/hostname."
categories: "common"
---
> More information: <https://github.com/imsnif/bandwhich>.

- Show the remote addresses table only:

```bash
bandwhich --addresses
```

- Show DNS queries:

```bash
bandwhich --show-dns
```

- Show total (cumulative) usage:

```bash
bandwhich --total-utilization
```

- Show the network utilization for a specific network interface:

```bash
bandwhich --interface eth0
```

- Show DNS queries with a given DNS server:

```bash
bandwhich --show-dns --dns-server dns_server_ip
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Florian B](mailto:gn0mish@protonmail.com) | bandwhich: add page (#5750) | 2021-04-19T20:53:58 | [3252dab36b59](https://github.com/tldr-pages/tldr/commit/3252dab36b59a29f7c2efb637537d3dd366e1440)

