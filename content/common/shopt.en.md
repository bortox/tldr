---
author: ['Sarah Haïm-Lubczanski', 'Waldir Pimenta']
date: 1635871124
title: "shopt"
description: "shopt, Manage Bash shell options: variables (stored in `$BASHOPTS`) that control behavior specific to the Bash shell."
categories: "common"
---
> Generic POSIX shell variables (stored in `$SHELLOPTS`) are managed with the `set` command instead.

> More information: <https://www.gnu.org/software/bash/manual/html_node/The-Shopt-Builtin.html>.

- List of all settable options and whether they are set:

```bash
shopt
```

- Set an option:

```bash
shopt -s option_name
```

- Unset an option:

```bash
shopt -u option_name
```

- Print a list of all options and their status formatted as runnable `shopt` commands:

```bash
shopt -p
```

- Show help for the command:

```bash
help shopt
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Sarah Haïm-Lubczanski](mailto:205895+mere-teresa@users.noreply.github.com) | shopt: add more information link (#7373) | 2021-11-02T17:38:44 | [2044ad9bf2a9](https://github.com/tldr-pages/tldr/commit/2044ad9bf2a9d67d69343c9272f9718043ffe3c5)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | shopt: add page (#1033) | 2016-09-28T09:29:44 | [67840a5c3fe9](https://github.com/tldr-pages/tldr/commit/67840a5c3fe9de2a7313787e34f67017397a8cbe)

