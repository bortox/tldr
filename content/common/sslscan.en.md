---
author: ['Pierre Rudloff']
date: 1637243132
title: "sslscan, TLDR Pages"
description: "sslscan, Check SSL/TLS protocols and ciphers supported by a server."
categories: "common"
---
> More information: <https://github.com/rbsec/sslscan>.

- Test a server on port 443:

```bash
sslscan example.com
```

- Test a specified port:

```bash
sslscan example.com:465
```

- Show certificate information:

```bash
testssl --show-certificate example.com
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Pierre Rudloff](mailto:contact@rudloff.pro) | sslscan: add page (#7451) | 2021-11-18T14:45:32 | [3d4465a5d67e](https://github.com/tldr-pages/tldr/commit/3d4465a5d67edf5d780e180d0b4be44dcc1d9597)

