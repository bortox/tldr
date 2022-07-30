---
author: ['marchersimon']
date: 1638354390
title: "orca-c"
description: "orca-c, A C-port of the ORCA live programming environment."
categories: "common"
---
> ORCA is an esoteric programming language for creating procedural sequencers.

> More information: <https://github.com/hundredrabbits/Orca-c>.

- Start ORCA with an empty workspace:

```bash
orca-c
```

- Start ORCA and open a specific file:

```bash
orca-c path/to/file.orca
```

- Start ORCA and set a specific tempo (defaults to 120):

```bash
orca-c --bpm beats_per_minute
```

- Start ORCA and set the size of the grid:

```bash
orca-c --initial-size columnsxrows
```

- Start ORCA and set the maximum number of undo steps (defaults to 100):

```bash
orca-c --undo-limit limit
```

- Show the main menu inside of ORCA:

```bash
F1
```

- Show all shortcuts inside of ORCA:

```bash
?
```

- Show all ORCA operators inside of ORCA:

```bash
Ctrl + g
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | orca-c: add page (#7494) | 2021-12-01T11:26:30 | [2d03e7f2b94a](https://github.com/tldr-pages/tldr/commit/2d03e7f2b94a460f18a7d2ce30a97a58fb06b1c1)

