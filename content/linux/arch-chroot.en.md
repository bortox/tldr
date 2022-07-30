---
author: ['Axel Navarro']
date: 1614292271
title: "arch-chroot"
description: "arch-chroot, Enhanced `chroot` command to help in the Arch Linux installation process."
categories: "linux"
---
> More information: <https://man.archlinux.org/man/arch-chroot.8>.

- Start an interactive shell (`bash`, by default) in a new root directory:

```bash
arch-chroot path/to/new/root
```

- Specify the user (other than the current user) to run the shell as:

```bash
arch-chroot -u user path/to/new/root
```

- Run a custom command (instead of the default `bash`) in the new root directory:

```bash
arch-chroot path/to/new/root command command_arguments
```

- Specify the shell, other than the default `bash` (in this case, the `zsh` package should have been installed in the target system):

```bash
arch-chroot path/to/new/root zsh
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Axel Navarro](mailto:navarroaxel@gmail.com) | arch-chroot: add page (#5248) * Apply suggestions from code review Co-authored-by: bl-ue <54780737+bl-ue@users.noreply.github.com> * [...] | 2021-02-25T23:31:11 | [01dbbf6f2698](https://github.com/tldr-pages/tldr/commit/01dbbf6f269821c6cc337a84b441243a681ac25e)

