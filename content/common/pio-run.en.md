---
author: ['marchersimon']
date: 1619326276
title: "pio run"
description: "pio run, Run PlatformIO project targets."
categories: "common"
---
> More information: <https://docs.platformio.org/en/latest/core/userguide/cmd_run.html>.

- List all available project targets:

```bash
pio run --list-targets
```

- List all available project targets of a specific environment:

```bash
pio run --list-targets --environment environment
```

- Run all targets:

```bash
pio run
```

- Run all targets of specified environments:

```bash
pio run --environment environment1 --environment environment2
```

- Run specified targets:

```bash
pio run --target target1 --target target2
```

- Run the targets of a specified configuration file:

```bash
pio run --project-conf path/to/platformio.ini
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | pio-run: add page (#5827) | 2021-04-25T06:51:16 | [32e86137f277](https://github.com/tldr-pages/tldr/commit/32e86137f277c8f98dc33b10da30c0316e8592b6)

