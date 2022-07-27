---
author: ['frcroth']
date: 1606439251
title: "airmon-ng, TLDR Pages"
description: "airmon-ng, Activate monitor mode on wireless network devices."
categories: "common"
---
> More information: <https://www.aircrack-ng.org/doku.php?id=airmon-ng>.

- List wireless devices and their statuses:

```bash
sudo airmon-ng
```

- Turn on monitor mode for a specific device:

```bash
sudo airmon-ng start wlan0
```

- Kill disturbing processes that use wireless devices:

```bash
sudo airmon-ng check kill
```

- Turn off monitor mode for a specific network interface:

```bash
sudo airmon-ng stop wlan0mon
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[frcroth](mailto:frcroth@users.noreply.github.com) | airmon-ng: add page (#4974) | 2020-11-27T02:07:31 | [c27417d566e4](https://github.com/tldr-pages/tldr/commit/c27417d566e47d555324adf6b0b5cead52d5859e)

