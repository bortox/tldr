---
author: ['Sahil Dhiman']
date: 1607108715
title: "resolveip, TLDR Pages"
description: "resolveip, Resolve hostnames to their IP addresses and vice versa."
categories: "linux"
---
> More information: <https://mariadb.com/kb/en/resolveip/>.

- Resolve a hostname to an IP address:

```bash
resolveip example.org
```

- Resolve an IP address to a hostname:

```bash
resolveip 1.1.1.1
```

- Silent mode. Produces less output:

```bash
resolveip --silent example.org
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Sahil Dhiman](mailto:52946452+sahilister@users.noreply.github.com) | resolveip: add page (#4982) | 2020-12-04T20:05:15 | [935d337cc678](https://github.com/tldr-pages/tldr/commit/935d337cc67878d2a1c3bdec52149ba5086995fb)

