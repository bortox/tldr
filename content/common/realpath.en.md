---
author: ['Dario Vladović', 'Felix Yan', 'marchersimon']
date: 1617292466
title: "realpath"
description: "realpath, Display the resolved absolute path for a file or directory."
categories: "common"
---
> More information: <https://www.gnu.org/software/coreutils/realpath>.

- Display the absolute path for a file or directory:

```bash
realpath path/to/file_or_directory
```

- Require all path components to exist:

```bash
realpath --canonicalize-existing path/to/file_or_directory
```

- Resolve ".." components before symlinks:

```bash
realpath --logical path/to/file_or_directory
```

- Disable symlink expansion:

```bash
realpath --no-symlinks path/to/file_or_directory
```

- Suppress error messages:

```bash
realpath --quiet path/to/file_or_directory
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Dario Vladović](mailto:d.vladimyr@gmail.com) | coreutils*: use short more info links (#5658) | 2021-04-01T17:54:26 | [4830093903f6](https://github.com/tldr-pages/tldr/commit/4830093903f66ccf3ebbc2ecf477286e45edac59)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | realpath: add link (#5565) | 2021-03-30T10:39:58 | [e87ab63d14b7](https://github.com/tldr-pages/tldr/commit/e87ab63d14b76e709f65fcb28375d3f1d2415d9e)
[Felix Yan](mailto:felixonmars@archlinux.org) | coreutils commands: move pages to common/ folder (#2442) | 2018-10-16T19:29:50 | [72b4f22ff97b](https://github.com/tldr-pages/tldr/commit/72b4f22ff97b1890344f2af870ad3d1c89a3f0b5)

