---
author: ['marchersimon']
date: 1625951782
title: "pio ci, TLDR Pages"
description: "pio ci, Build PlatformIO projects with an arbitrary source code structure."
categories: "common"
---
> This will create a new temporary project which the source code will be copied into.

> More information: <https://docs.platformio.org/en/latest/core/userguide/cmd_ci.html>.

- Build a PlatformIO project in the default system temporary directory and delete it afterwards:

```bash
pio ci path/to/project
```

- Build a PlatformIO project and specify specific libraries:

```bash
pio ci --lib path/to/library_directory path/to/project
```

- Build a PlatformIO project and specify a specific board (`pio boards` lists all of them):

```bash
pio ci --board board path/to/project
```

- Build a PlatformIO project in a specific directory:

```bash
pio ci --build-dir path/to/build_directory path/to/project
```

- Build a PlatformIO project and don't delete the build directory:

```bash
pio ci --keep-build-dir path/to/project
```

- Build a PlatformIO project using a specific configuration file:

```bash
pio ci --project-conf path/to/platformio.ini
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | pio-ci: add page (#6186) | 2021-07-10T23:16:22 | [73ee6f771b94](https://github.com/tldr-pages/tldr/commit/73ee6f771b9490281742aa4353ecb3115cd57819)

