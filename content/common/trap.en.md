---
author: ['marchersimon']
date: 1632060820
title: "trap, TLDR Pages"
description: "trap, Automatically execute commands after receiving signals by processes or the operating system."
categories: "common"
---
> Can be used to perform cleanups for interruptions by the user or other actions.

> More information: <https://manned.org/trap>.

- List available signals to set traps for:

```bash
trap -l
```

- List active traps for the current shell:

```bash
trap -p
```

- Set a trap to execute commands when one or more signals are detected:

```bash
trap 'echo "Caught signal SIGHUP"' SIGHUP
```

- Remove active traps:

```bash
trap - SIGHUP SIGINT
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | pwgen, sshuttle, trap, tree: move to common (#6551) | 2021-09-19T16:13:40 | [6474a3284244](https://github.com/tldr-pages/tldr/commit/6474a3284244a623c5ba32264a99d6a27a3bcce3)

