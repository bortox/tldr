---
author: ['Dario Vladović', 'Jonathan Chen', 'jack1142', 'rprieto', 'Alessio', 'Matthew Peveler', 'Ruben Vereecken']
date: 1621596558
title: "mv"
description: "mv, Move or rename files and directories."
categories: "common"
---
> More information: <https://www.gnu.org/software/coreutils/mv>.

- Move a file to an arbitrary location:

```bash
mv source target
```

- Move files into another directory, keeping the filenames:

```bash
mv source1 source2 source3 target_directory
```

- Do not prompt for confirmation before overwriting existing files:

```bash
mv -f source target
```

- Prompt for confirmation before overwriting existing files, regardless of file permissions:

```bash
mv -i source target
```

- Do not overwrite existing files at the target:

```bash
mv -n source target
```

- Move files in verbose mode, showing files after they are moved:

```bash
mv -v source target
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[jack1142](mailto:6032823+jack1142@users.noreply.github.com) | mv: add move multiple source paths to a directory example (#6004) | 2021-05-21T13:29:18 | [bf009c27ccd8](https://github.com/tldr-pages/tldr/commit/bf009c27ccd8efece7b42983903ddf81e23851d7)
[Dario Vladović](mailto:d.vladimyr@gmail.com) | coreutils*: use short more info links (#5658) | 2021-04-01T17:54:26 | [4830093903f6](https://github.com/tldr-pages/tldr/commit/4830093903f66ccf3ebbc2ecf477286e45edac59)
[Alessio](mailto:25589202+tomadojuice@users.noreply.github.com) | mv: add more information link (#5542) | 2021-03-29T20:24:45 | [45ff3b27a290](https://github.com/tldr-pages/tldr/commit/45ff3b27a290a760ee43340226e4e85e2091dbfc)
[Matthew Peveler](mailto:matt.peveler@gmail.com) | mv: fix -i example and add -n example (#2482) | 2018-10-24T00:18:41 | [26c0f8eefde4](https://github.com/tldr-pages/tldr/commit/26c0f8eefde425c4c10e91942eff6c847af7120e)
[Jonathan Chen](mailto:dijonkitchen@users.noreply.github.com) | Fix spelling error (#846) | 2016-04-10T21:06:07 | [2045afb9aa90](https://github.com/tldr-pages/tldr/commit/2045afb9aa90a1f52b02d1507ddca56f5897be96)
[Ruben Vereecken](mailto:rubenvereecken@gmail.com) | Formatted all pages according to guidelines. | 2016-01-08T09:38:59 | [066582e8eab5](https://github.com/tldr-pages/tldr/commit/066582e8eab57bce9861cc8d379e158d61f1cc95)
[rprieto](mailto:choicesmade@gmail.com) | Move pages back into a "pages" folder | 2014-03-04T13:28:29 | [f00bf64426a7](https://github.com/tldr-pages/tldr/commit/f00bf64426a792ee3aac792f9c0aec3f8b1eaa7d)

