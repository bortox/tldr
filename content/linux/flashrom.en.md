---
author: ['Seth Falco', 'Peter Babič']
date: 1629050349
title: "flashrom"
description: "flashrom, Read, write, verify and erase flash chips."
categories: "linux"
---
> More information: <https://manned.org/flashrom>.

- Probe the chip, ensuring the wiring is correct:

```bash
flashrom --programmer programmer
```

- Read flash and save it to a file:

```bash
flashrom -p programmer --read path/to/file
```

- Write a file to the flash:

```bash
flashrom -p programmer --write path/to/file
```

- Verify the flash against a file:

```bash
flashrom -p programmer --verify path/to/file
```

- Probe the chip using Raspberry Pi:

```bash
flashrom -p linux_spi:dev=/dev/spidev0.0
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Seth Falco](mailto:seth@falco.fun) | *: fix errors reported by languagetool (#6069) | 2021-08-15T19:59:09 | [3e4c519004a4](https://github.com/tldr-pages/tldr/commit/3e4c519004a471c861cdc609fd7239ee3355671c)
[Peter Babič](mailto:peter@babic.dev) | flashrom: add page (#5700) | 2021-04-10T00:35:57 | [dea027f28f0f](https://github.com/tldr-pages/tldr/commit/dea027f28f0f68f70ba3fd98ee510401fafe78b0)

