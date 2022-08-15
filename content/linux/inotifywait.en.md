---
author: ['Lucas Gabriel Schneider', 'marchersimon', 'Paweł Sacawa', 'hugo', 'CleanMachine1']
date: 1660446102
title: "inotifywait"
description: "inotifywait, Waits for changes to one or more files."
categories: "linux"
---
> More information: <https://manned.org/inotifywait>.

- Watch a specific file for events, exiting after the first one:

```bash
inotifywait path/to/file
```

- Continuously watch a specific file for events without exiting:

```bash
inotifywait --monitor path/to/file
```

- Watch a directory recursively for events:

```bash
inotifywait --monitor --recursive path/to/directory
```

- Watch a directory for changes, excluding files, whose names match a regular expression:

```bash
inotifywait --monitor --recursive --exclude "regular_expression" path/to/directory
```

- Watch a file for changes, exiting when no event occurs for 30 seconds:

```bash
inotifywait --monitor --timeout 30 path/to/file
```

- Only watch a file for file modification events:

```bash
inotifywait --event modify path/to/file
```

- Watch a file printing only events, and no status messages:

```bash
inotifywait --quiet path/to/file
```

- Run a command when a file is accessed:

```bash
inotifywait --event access path/to/file && command
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | inotifywait: refresh (#8323) | 2022-08-14T05:01:42 | [bb28b5eccdfd](https://github.com/tldr-pages/tldr/commit/bb28b5eccdfddec3119b111ba3f9252103651715)
[CleanMachine1](mailto:78213164+CleanMachine1@users.noreply.github.com) | inotifywait: add --monitor command (#8278) | 2022-08-08T19:12:39 | [6d4dc061c51a](https://github.com/tldr-pages/tldr/commit/6d4dc061c51a9717d4de6ef206cdffa9688455aa)
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | linux/[h-k]: add more information link (#6227) | 2021-09-02T20:33:49 | [65456d0941d0](https://github.com/tldr-pages/tldr/commit/65456d0941d092a69548cae0ed6e4f4d19bfe9d2)
[hugo](mailto:rivten.grey@gmail.com) | inotifywait: fix typo (#6298) | 2021-08-05T14:56:47 | [167da9b43215](https://github.com/tldr-pages/tldr/commit/167da9b4321516b5e6c2c4b2e3d347457e4a1e99)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | multiple pages: normalize `regular expression` instead of `regex`, `regexp` or `pattern` (#5830) | 2021-05-10T11:03:12 | [10728f1ab485](https://github.com/tldr-pages/tldr/commit/10728f1ab485957d66af3940a030b0fb77611fc0)
[Paweł Sacawa](mailto:psacawa@math.toronto.edu) | inotifywait: fix misnamed command (#4495) | 2020-10-05T12:33:17 | [04d1dcf83882](https://github.com/tldr-pages/tldr/commit/04d1dcf8388200f021fe97afae1cb115c5ae1c0c)

