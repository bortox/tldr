---
author: ['Max Strübing', 'syleung']
date: 1633517967
title: "ping6, TLDR Pages"
description: "ping6, Send ICMP ECHO_REQUEST packets to network hosts via IPv6 address."
categories: "common"
---
> More information: <https://manned.org/ping6>.

- Ping a host:

```bash
ping6 host
```

- Ping a host only a specific number of times:

```bash
ping6 -c count host
```

- Ping a host, specifying the interval in seconds between requests (default is 1 second):

```bash
ping6 -i seconds host
```

- Ping a host without trying to lookup symbolic names for addresses:

```bash
ping6 -n host
```

- Ping a host and ring the bell when a packet is received (if your terminal supports it):

```bash
ping6 -a host
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[syleung](mailto:syleung@users.noreply.github.com) | ping, ping6: add more information link (#6658) | 2021-10-06T12:59:27 | [4efa36e763c9](https://github.com/tldr-pages/tldr/commit/4efa36e763c9485e45704136ac7c588b350e6657)
[Max Strübing](mailto:mxstrbng@gmail.com) | ping6: add page (#1982) | 2018-02-10T07:35:16 | [765e000347e8](https://github.com/tldr-pages/tldr/commit/765e000347e8a78b444249e852a6f3ebe14a862e)

