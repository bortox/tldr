---
author: ['Pierre Rudloff']
date: 1643507490
title: "ubuntu-security-status, TLDR Pages"
description: "ubuntu-security-status, Display information about security support for installed Ubuntu packages."
categories: "linux"
---
> More information: <https://git.launchpad.net/ubuntu/+source/update-manager/tree/ubuntu-security-status>.

- Display the number of unsupported packages:

```bash
ubuntu-security-status
```

- List packages that are no longer available for download:

```bash
ubuntu-security-status --unavailable
```

- List third-party packages:

```bash
ubuntu-security-status --thirdparty
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Pierre Rudloff](mailto:contact@rudloff.pro) | ubuntu-security-status: add page (#7728) | 2022-01-30T02:51:30 | [09f8f802d389](https://github.com/tldr-pages/tldr/commit/09f8f802d3898051974117a3af5f3b64a92329f7)

