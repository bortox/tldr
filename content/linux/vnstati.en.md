---
author: ['Melvin']
date: 1626527478
title: "vnstati"
description: "vnstati, PNG image output support for vnStat."
categories: "linux"
---
> More information: <https://manned.org/vnstati>.

- Output a summary of the last 2: months, days, and all-time:

```bash
vnstati --summary --iface network_interface --output path/to/output.png
```

- Output the 10 most traffic-intensive days of all time:

```bash
vnstati --top10 --iface network_interface --output path/to/output.png
```

- Output monthly traffic statistics from the last 12 months:

```bash
vnstati --months --iface network_interface --output path/to/output.png
```

- Output hourly traffic statistics from the last 24 hours:

```bash
vnstati --hours --iface network_interface --output path/to/output.png
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Melvin](mailto:github@melvin2204.nl) | vnstati: add page (#6175) | 2021-07-17T15:11:18 | [3d075993577b](https://github.com/tldr-pages/tldr/commit/3d075993577b451bd3b3b59cc65adad8a471e62a)

