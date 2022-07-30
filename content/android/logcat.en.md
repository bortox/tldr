---
author: ['marchersimon']
date: 1620637392
title: "logcat"
description: "logcat, Dump a log of system messages."
categories: "android"
---
> More information: <https://developer.android.com/studio/command-line/logcat>.

- Display system logs:

```bash
logcat
```

- Write system logs to a file:

```bash
logcat -f path/to/file
```

- Display lines that match a regular expression:

```bash
logcat --regex regular_expression
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | multiple pages: normalize `regular expression` instead of `regex`, `regexp` or `pattern` (#5830) | 2021-05-10T11:03:12 | [10728f1ab485](https://github.com/tldr-pages/tldr/commit/10728f1ab485957d66af3940a030b0fb77611fc0)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | android/*: fix command descriptions (#5807) | 2021-04-22T22:09:21 | [4b891616c6a1](https://github.com/tldr-pages/tldr/commit/4b891616c6a1f21e836b56d216b7ec008e1dd746)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | logcat: move to android/ (#5737) | 2021-04-12T19:52:22 | [fd625e15e12b](https://github.com/tldr-pages/tldr/commit/fd625e15e12b7510015b43dfee7f5fa8b40df7a6)

