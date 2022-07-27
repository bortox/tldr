---
author: ['Tomek Szczęsny']
date: 1620983677
title: "distccd, TLDR Pages"
description: "distccd, Server daemon for the distcc distributed compiler."
categories: "common"
---
> More information: <https://distcc.github.io>.

- Start a daemon with the default settings:

```bash
distccd --daemon
```

- Start a daemon, accepting connections from IPv4 private network ranges:

```bash
distccd --daemon --allow-private
```

- Start a daemon, accepting connections from a specific network address or address range:

```bash
distccd --daemon --allow ip_address|network_prefix
```

- Start a daemon with a lowered priority that can run a maximum of 4 tasks at a time:

```bash
distccd --daemon --jobs 4 --nice 5
```

- Start a daemon and register it via mDNS/DNS-SD (Zeroconf):

```bash
distccd --daemon --zeroconf
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Tomek Szczęsny](mailto:44300715+tomek-szczesny@users.noreply.github.com) | distccd: add page (#5912) | 2021-05-14T11:14:37 | [c1b5d6882b9e](https://github.com/tldr-pages/tldr/commit/c1b5d6882b9ef922a1fbbc83096dcfa699867ddf)

