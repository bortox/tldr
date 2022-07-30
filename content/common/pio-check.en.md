---
author: ['marchersimon']
date: 1616955998
title: "pio check"
description: "pio check, Perform a static analysis check on a PlatformIO project."
categories: "common"
---
> More information: <https://docs.platformio.org/en/latest/core/userguide/cmd_check.html>.

- Perform a basic analysis check on the current project:

```bash
pio check
```

- Perform a basic analysis check on a specific project:

```bash
pio check --project-dir project_dir
```

- Perform an analysis check for a specific environment:

```bash
pio check --environment environment
```

- Perform an analysis check and only report a specified defect severity type:

```bash
pio check --severity low|medium|high
```

- Perform an analysis check and show detailed information when processing environments:

```bash
pio check --verbose
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | pio-check: add page (#5519) | 2021-03-28T20:26:38 | [5c9261d7fde1](https://github.com/tldr-pages/tldr/commit/5c9261d7fde140d8fd8f22873d184db2eb49a090)

