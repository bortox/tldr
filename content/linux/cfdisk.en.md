---
author: ['Mat', 'marchersimon']
date: 1618584134
title: "cfdisk, TLDR Pages"
description: "cfdisk, A program for managing partition tables and partitions on a hard disk using a curses UI."
categories: "linux"
---
> More information: <https://manned.org/cfdisk>.

- Start the partition manipulator with a specific device:

```bash
cfdisk /dev/sdX
```

- Create a new partition table for a specific device and manage it:

```bash
cfdisk --zero /dev/sdX
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | multiple pages: replace all die.net links (#5528) Most of the links were replaced by manned.org, except when there are more up-to-date [...] | 2021-04-16T16:42:14 | [dac4a710772f](https://github.com/tldr-pages/tldr/commit/dac4a710772f9adef5b9883172fb30ed2416c0eb)
[Mat](mailto:mtausig@users.noreply.github.com) | cfdisk: add page (#4881) | 2020-10-28T19:39:33 | [15fa534d4b55](https://github.com/tldr-pages/tldr/commit/15fa534d4b55fb6a509d49f1f195cf13f2b2c253)

