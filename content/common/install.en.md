---
author: ['Dario Vladović', 'Krutonium', 'Reinhart Previano Koentjoro', 'Assem Attia', 'Seth Falco', 'marchersimon']
date: 1647565731
title: "install"
description: "install, Copy files and set attributes."
categories: "common"
---
> Copy files (often executable) to a system location like `/usr/local/bin`, give them the appropriate permissions/ownership.

> More information: <https://www.gnu.org/software/coreutils/install>.

- Copy files to the destination:

```bash
install path/to/source_file1 path/to/source_file2 ... path/to/destination
```

- Copy files to the destination, setting their ownership:

```bash
install --owner user path/to/source_file1 path/to/source_file2 ... path/to/destination
```

- Copy files to the destination, setting their group ownership:

```bash
install --group user path/to/source_file1 path/to/source_file2 ... path/to/destination
```

- Copy files to the destination, setting their `mode`:

```bash
install --mode +x path/to/source_file1 path/to/source_file2 ... path/to/destination
```

- Copy files and apply access/modification times of source to the destination:

```bash
install --preserve-timestamps path/to/source_file1 path/to/source_file2 ... path/to/destination
```

- Copy files and create the directories at the destination if they don't exist:

```bash
install -D path/to/source_file1 path/to/source_file2 ... path/to/destination
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Krutonium](mailto:3945538+Krutonium@users.noreply.github.com) | install: add -D example (#7803) * Add example for creating directories along the path * Update pages/common/install.md Co-authored-by: [...] | 2022-03-18T02:08:51 | [b209b606ceda](https://github.com/tldr-pages/tldr/commit/b209b606ceda3ca60c5fb6f60f301e4e922f9e78)
[Reinhart Previano Koentjoro](mailto:reinhart_previano@yahoo.com) | install: use long arguments format (#7403) | 2021-11-10T09:51:46 | [87e3e877fa3d](https://github.com/tldr-pages/tldr/commit/87e3e877fa3d6c0d7d2a7fe5100c908c76de8f57)
[Seth Falco](mailto:seth@falco.fun) | *: fix errors reported by languagetool (#6069) | 2021-08-15T19:59:09 | [3e4c519004a4](https://github.com/tldr-pages/tldr/commit/3e4c519004a471c861cdc609fd7239ee3355671c)
[Dario Vladović](mailto:d.vladimyr@gmail.com) | coreutils*: use short more info links (#5658) | 2021-04-01T17:54:26 | [4830093903f6](https://github.com/tldr-pages/tldr/commit/4830093903f66ccf3ebbc2ecf477286e45edac59)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | install: add link (#5559) | 2021-03-30T09:30:44 | [718ea2fa10dc](https://github.com/tldr-pages/tldr/commit/718ea2fa10dc125e48e3fb10b3e8b8adbb86c0d0)
[Assem Attia](mailto:assem.m.ahmad@gmail.com) | install: add page (#1140) | 2016-12-22T00:37:17 | [b88b9ba3c7a8](https://github.com/tldr-pages/tldr/commit/b88b9ba3c7a82659f503b5a3224ed1f7cb236698)

