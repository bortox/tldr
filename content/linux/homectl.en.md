---
author: ['Axel Navarro', 'git-em']
date: 1646800268
title: "homectl, TLDR Pages"
description: "homectl, Create, remove, change or inspect home directories using the systemd-homed service."
categories: "linux"
---
> More information: <https://manned.org/homectl>.

- List user accounts and their associated home directories:

```bash
homectl list
```

- Create a user account and their associated home directory:

```bash
sudo homectl create username
```

- Remove a specific user and the associated home directory:

```bash
sudo homectl remove username
```

- Change the password for a specific user:

```bash
sudo homectl passwd username
```

- Run a shell or a command with access to a specific home directory:

```bash
sudo homectl with username -- command command_arguments
```

- Lock or unlock a specific home directory:

```bash
sudo homectl lock|unlock username
```

- Change the disk space assigned to a specific home directory to 100 GiB:

```bash
sudo homectl resize username 100G
```

- Display help:

```bash
homectl --help
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[git-em](mailto:56173216+git-em@users.noreply.github.com) | linux/*: replace man.archlinux.com link (#7861) * linux/*: replace man.archlinux.com Does not replace links of pages directly [...] | 2022-03-09T05:31:08 | [8628cba2ebf0](https://github.com/tldr-pages/tldr/commit/8628cba2ebf0939f9aec27530c42351215334eeb)
[Axel Navarro](mailto:navarroaxel@gmail.com) | homectl: add page (#5688) | 2021-04-13T15:35:21 | [660d097d9c94](https://github.com/tldr-pages/tldr/commit/660d097d9c94f5dbeedbdadda99cda1798d44488)

