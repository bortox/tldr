---
author: ['Paweł Sacawa', 'marchersimon', 'Lucas Gabriel Schneider', 'hugo']
date: 1630607629
title: "inotifywait, TLDR Pages"
description: "inotifywait, Waits for changes to one or more files."
categories: "linux"
---
> More information: <https://manned.org/inotifywait>.

- Run a command when a file changes:

```bash
while inotifywait path/to/file; do command; done
```

- Be quiet about watching for changes:

```bash
while inotifywait --quiet path/to/file; do command; done
```

- Watch a directory recursively for changes:

```bash
while inotifywait --recursive path/to/directory; do command; done
```

- Exclude files matching a regular expression:

```bash
while inotifywait --recursive path/to/directory --exclude 'regular_expression'; do command; done
```

- Wait at most 30 seconds:

```bash
while inotifywait --timeout 30 path/to/file; do command; done
```

- Only watch for file modification events:

```bash
while inotifywait --event modify path/to/file; do command; done
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | linux/[h-k]: add more information link (#6227) | 2021-09-02T20:33:49 | [65456d0941d0](https://github.com/tldr-pages/tldr/commit/65456d0941d092a69548cae0ed6e4f4d19bfe9d2)
[hugo](mailto:rivten.grey@gmail.com) | inotifywait: fix typo (#6298) | 2021-08-05T14:56:47 | [167da9b43215](https://github.com/tldr-pages/tldr/commit/167da9b4321516b5e6c2c4b2e3d347457e4a1e99)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | multiple pages: normalize `regular expression` instead of `regex`, `regexp` or `pattern` (#5830) | 2021-05-10T11:03:12 | [10728f1ab485](https://github.com/tldr-pages/tldr/commit/10728f1ab485957d66af3940a030b0fb77611fc0)
[Paweł Sacawa](mailto:psacawa@math.toronto.edu) | inotifywait: fix misnamed command (#4495) | 2020-10-05T12:33:17 | [04d1dcf83882](https://github.com/tldr-pages/tldr/commit/04d1dcf8388200f021fe97afae1cb115c5ae1c0c)

