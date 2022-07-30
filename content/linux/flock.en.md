---
author: ['Xiang Wang']
date: 1629903781
title: "flock"
description: "flock, Manage locks from shell scripts."
categories: "linux"
---
> It can be used to ensure that only one process of a command is running.

> More information: <https://manned.org/flock>.

- Run a command with a file lock as soon as the lock is not required by others:

```bash
flock path/to/lock.lock --command "command"
```

- Run a command with a file lock, and exit if the lock doesn't exist:

```bash
flock path/to/lock.lock --nonblock --command "command"
```

- Run a command with a file lock, and exit with a specific error code if the lock doesn't exist:

```bash
flock path/to/lock.lock --nonblock --conflict-exit-code error_code -c "command"
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Xiang Wang](mailto:ramwin@qq.com) | flock: add page (#6390) | 2021-08-25T17:03:01 | [ec23b7115c5c](https://github.com/tldr-pages/tldr/commit/ec23b7115c5c318a03ab27047a90ac95c6e424bf)

