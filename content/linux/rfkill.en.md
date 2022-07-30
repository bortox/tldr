---
author: ['Emily Grace Seville', 'Sacha Bron']
date: 1647882468
title: "rfkill"
description: "rfkill, Enable and disable wireless devices."
categories: "linux"
---
> More information: <https://manned.org/rfkill>.

- List devices:

```bash
rfkill
```

- Filter by columns:

```bash
rfkill -o ID,TYPE,DEVICE
```

- Block devices by type (e.g. bluetooth, wlan):

```bash
rfkill block bluetooth
```

- Unblock devices by type (e.g. bluetooth, wlan):

```bash
rfkill unblock wlan
```

- Output in JSON format:

```bash
rfkill -J
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Emily Grace Seville](mailto:emilyseville7cf@gmail.com) | linux/*: add more information link (#7848) | 2022-03-21T18:07:48 | [4659bcb243ac](https://github.com/tldr-pages/tldr/commit/4659bcb243ac572c9e0c95117097801f1e62bda4)
[Sacha Bron](mailto:BinaryBrain@users.noreply.github.com) | rfkill: add page (#2502) | 2018-10-31T01:15:22 | [201bf8428ed0](https://github.com/tldr-pages/tldr/commit/201bf8428ed07bed3c8dd33a975a56bcf1db2d41)

