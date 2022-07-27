---
author: ['Seth Falco', 'Starbeamrainbowlabs']
date: 1629050349
title: "solo, TLDR Pages"
description: "solo, Interact with Solo hardware security keys."
categories: "common"
---
> More information: <https://github.com/solokeys/solo-python>.

- List connected Solos:

```bash
solo ls
```

- Update the currently connected Solo's firmware to the latest version:

```bash
solo key update
```

- Blink the LED of a specific Solo:

```bash
solo key wink --serial serial_number
```

- Generate random bytes using the currently connected Solo's secure random number generator:

```bash
solo key rng raw
```

- Monitor the serial output of a Solo:

```bash
solo monitor path/to/serial_port
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Seth Falco](mailto:seth@falco.fun) | *: fix errors reported by languagetool (#6069) | 2021-08-15T19:59:09 | [3e4c519004a4](https://github.com/tldr-pages/tldr/commit/3e4c519004a471c861cdc609fd7239ee3355671c)
[Starbeamrainbowlabs](mailto:sbrl@starbeamrainbowlabs.com) | solo: add page (#3146) | 2019-06-28T11:34:01 | [241155bfd72d](https://github.com/tldr-pages/tldr/commit/241155bfd72de97c9b22ebddb7e66ac2dfa87cf9)

