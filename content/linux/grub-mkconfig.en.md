---
author: ['bl-ue']
date: 1614935989
title: "grub-mkconfig, TLDR Pages"
description: "grub-mkconfig, Generate a GRUB configuration file."
categories: "linux"
---
> More information: <https://www.gnu.org/software/grub/manual/grub/html_node/Invoking-grub_002dmkconfig.html>.

- Do a dry run and print the configuration to stdout:

```bash
sudo grub-mkconfig
```

- Generate the configuration file:

```bash
sudo grub-mkconfig --output=/boot/grub/grub.cfg
```

- Print the help page:

```bash
grub-mkconfig --help
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | grub-mkconfig: move from / to pages/linux (#5350) | 2021-03-05T10:19:49 | [a5af5c802b91](https://github.com/tldr-pages/tldr/commit/a5af5c802b910a0d8e5efc9fb4173dd03b22822a)

