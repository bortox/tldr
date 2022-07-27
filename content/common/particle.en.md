---
author: ['Owen Voke']
date: 1570576287
title: "particle, TLDR Pages"
description: "particle, A command-line tool for interacting with Particle devices."
categories: "common"
---
> More information: <https://docs.particle.io/tutorials/developer-tools/cli>.

- Log in or create an account for the Particle CLI:

```bash
particle setup
```

- Display a list of devices:

```bash
particle list
```

- Create a new Particle project interactively:

```bash
particle project create
```

- Compile a Particle project:

```bash
particle compile device_type path/to/source_code.ino
```

- Update a device to use a specific app remotely:

```bash
particle flash device_name path/to/program.bin
```

- Update a device to use the latest firmware via serial:

```bash
particle flash --serial path/to/firmware.bin
```

- Execute a function on a device:

```bash
particle call device_name function_name function_arguments
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Owen Voke](mailto:owzie123@gmail.com) | particle: add page (#3356) | 2019-10-09T01:11:27 | [5ad73d10f3db](https://github.com/tldr-pages/tldr/commit/5ad73d10f3db7818f39c8edb7635587d5bcd142f)

