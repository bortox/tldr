---
author: ['IACS CSU 2020']
date: 1633925917
title: "runlim, TLDR Pages"
description: "runlim, A tool for sampling and limiting time and memory usage of a program and its child processes using the proc file system on Linux."
categories: "linux"
---
> More information: <http://fmv.jku.at/runlim>.

- Print the time and memory usage of a command:

```bash
runlim command command_arguments
```

- Log statistics to a file instead of stdout:

```bash
runlim --output-file=path/to/file command command_arguments
```

- Limit time to an upper bound (in seconds):

```bash
runlim --time-limit=number command command_arguments
```

- Limit real-time to an upper bound (in seconds):

```bash
runlim --real-time-limit=number command command_arguments
```

- Limit space to an upper bound (in MB):

```bash
runlim --space-limit=number command command_arguments
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[IACS CSU 2020](mailto:87594404+iacs-csu-2020@users.noreply.github.com) | python3, runlim: add page (#6937) | 2021-10-11T06:18:37 | [786b59a49676](https://github.com/tldr-pages/tldr/commit/786b59a4967633889b3fbdab2aad19f83e70173e)

