---
author: ['Tomek Szczęsny', 'Felix Yan', 'Dario Vladović', 'marchersimon']
date: 1622156322
title: "stty, TLDR Pages"
description: "stty, Set options for a terminal device interface."
categories: "common"
---
> More information: <https://www.gnu.org/software/coreutils/stty>.

- Display all settings for the current terminal:

```bash
stty -a
```

- Set the number of rows:

```bash
stty rows rows
```

- Set the number of columns:

```bash
stty cols cols
```

- Get the actual transfer speed of a device:

```bash
stty -F path/to/device_file speed
```

- Reset all modes to reasonable values for the current terminal:

```bash
stty sane
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Tomek Szczęsny](mailto:44300715+tomek-szczesny@users.noreply.github.com) | stty: fix typo (#6055) According to `stty --help`, the `-F` argument must be capital (lowercase is not recognized). Some Asian [...] | 2021-05-28T00:58:42 | [404065adae45](https://github.com/tldr-pages/tldr/commit/404065adae45d6460e0567046ba4ce2a2db85811)
[Dario Vladović](mailto:d.vladimyr@gmail.com) | coreutils*: use short more info links (#5658) | 2021-04-01T17:54:26 | [4830093903f6](https://github.com/tldr-pages/tldr/commit/4830093903f66ccf3ebbc2ecf477286e45edac59)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | stty: add link (#5628) | 2021-03-30T16:01:53 | [bb744d7f2725](https://github.com/tldr-pages/tldr/commit/bb744d7f27251d9525afd9f72714779f6044cf75)
[Felix Yan](mailto:felixonmars@archlinux.org) | coreutils commands: move pages to common/ folder (#2442) | 2018-10-16T19:29:50 | [72b4f22ff97b](https://github.com/tldr-pages/tldr/commit/72b4f22ff97b1890344f2af870ad3d1c89a3f0b5)

