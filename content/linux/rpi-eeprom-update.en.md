---
author: ['CleanMachine1']
date: 1658320876
title: "rpi-eeprom-update"
description: "rpi-eeprom-update, Tool to update EEPROM and view other EEPROM information."
categories: "linux"
---
> More information: <https://www.raspberrypi.com/documentation/computers/raspberry-pi.html#rpi-eeprom-update>.

- Print information about the current raspberry pi EEPROM installed:

```bash
sudo rpi-eeprom-update
```

- Update a raspberry pi EEPROM:

```bash
sudo rpi-eeprom-update -a
```

- Cancel the pending update:

```bash
sudo rpi-eeprom-update -r
```

- Display help:

```bash
rpi-eeprom-update -h
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[CleanMachine1](mailto:78213164+CleanMachine1@users.noreply.github.com) | rpi-eeprom-update: add page (#8195) | 2022-07-20T14:41:16 | [4ef9aa731f94](https://github.com/tldr-pages/tldr/commit/4ef9aa731f943e47ebeaa5a7f4b32795206d8974)

