---
author: ['Adam Herst']
date: 1623962386
title: "partprobe"
description: "partprobe, Notify the operating system kernel of partition table changes."
categories: "linux"
---
> More information: <https://manned.org/partprobe>.

- Notify the operating system kernel of partition table changes:

```bash
sudo partprobe
```

- Notify the kernel of partition table changes and show a summary of devices and their partitions:

```bash
sudo partprobe --summary
```

- Show a summary of devices and their partitions but don't notify the kernel:

```bash
sudo partprobe --summary --dry-run
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Adam Herst](mailto:adamherst@adamherst.com) | partprobe: add page (#6129) | 2021-06-17T22:39:46 | [d5c86c927e9f](https://github.com/tldr-pages/tldr/commit/d5c86c927e9f4e0cd3721af633e9b6d7938b920f)

