---
author: ['skitau']
date: 1602058065
title: "psping"
description: "psping, A ping tool that includes TCP ping, latency and bandwidth measurement."
categories: "windows"
---
> More information: <https://docs.microsoft.com/sysinternals/downloads/psping>.

- Ping a host using ICMP:

```bash
psping hostname
```

- Ping a host over a TCP port:

```bash
psping hostname:port
```

- Specify the number of pings and perform it quietly:

```bash
psping hostname -n pings -q
```

- Ping the target over TCP 50 times and produce a histogram of the results:

```bash
psping hostname:port -q -n 50 -h
```

- Display usage information:

```bash
psping /?
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[skitau](mailto:robert@blackstock.id.au) | psping: add page (#4514) | 2020-10-07T10:07:45 | [54258ff2e0df](https://github.com/tldr-pages/tldr/commit/54258ff2e0dfecf108ac0134b8946bbe72614752)

