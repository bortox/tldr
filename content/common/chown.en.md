---
author: ['Dario Vladović', 'Igor Shubovych', 'André König', 'Hayden Schiff', 'rprieto', 'lord63', 'Marco Bonelli', 'Ruben Vereecken', 'marchersimon']
date: 1617292466
title: "chown"
description: "chown, Change user and group ownership of files and directories."
categories: "common"
---
> More information: <https://www.gnu.org/software/coreutils/chown>.

- Change the owner user of a file/directory:

```bash
chown user path/to/file_or_directory
```

- Change the owner user and group of a file/directory:

```bash
chown user:group path/to/file_or_directory
```

- Recursively change the owner of a directory and its contents:

```bash
chown -R user path/to/directory
```

- Change the owner of a symbolic link:

```bash
chown -h user path/to/symlink
```

- Change the owner of a file/directory to match a reference file:

```bash
chown --reference=path/to/reference_file path/to/file_or_directory
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Dario Vladović](mailto:d.vladimyr@gmail.com) | coreutils*: use short more info links (#5658) | 2021-04-01T17:54:26 | [4830093903f6](https://github.com/tldr-pages/tldr/commit/4830093903f66ccf3ebbc2ecf477286e45edac59)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | chown: add more information link (#5555) | 2021-03-30T15:29:42 | [8d147522d127](https://github.com/tldr-pages/tldr/commit/8d147522d127f65aca087b791bf2deb46a43f59d)
[Marco Bonelli](mailto:mb5.marcob@gmail.com) | Refactor: change "folder" to "directory" where needed. This commit fixes every instance in which the word "folder" is incorrectly used [...] | 2019-02-13T16:21:04 | [2599a6de483a](https://github.com/tldr-pages/tldr/commit/2599a6de483a70601ab17b29e0f18a5a8bdcaa12)
[Marco Bonelli](mailto:mb5.marcob@gmail.com) | Refactor: add missing `or_directory` where needed. This commit adds the missing `_or_directory` to any example which is specifying an [...] | 2019-02-08T20:43:24 | [f79f6011e0f2](https://github.com/tldr-pages/tldr/commit/f79f6011e0f298311848b5f38d66c309d4b92665)
[Igor Shubovych](mailto:igor.shubovych@gmail.com) | Linting | 2016-02-23T02:54:19 | [ab54477533c8](https://github.com/tldr-pages/tldr/commit/ab54477533c8d173fa4d30cf3146ac7c450d54d6)
[Hayden Schiff](mailto:oxguy3@gmail.com) | chown: tweaks for parity with chgrp.md | 2016-02-22T21:07:35 | [3d6ae2325f5f](https://github.com/tldr-pages/tldr/commit/3d6ae2325f5f1f8ef03e71f3309808aeefea9d21)
[Ruben Vereecken](mailto:rubenvereecken@gmail.com) | Formatted all pages according to guidelines. | 2016-01-08T09:38:59 | [066582e8eab5](https://github.com/tldr-pages/tldr/commit/066582e8eab57bce9861cc8d379e158d61f1cc95)
[lord63](mailto:lord63.j@gmail.com) | Fix lint for common | 2015-10-23T02:02:34 | [56a7cba6568f](https://github.com/tldr-pages/tldr/commit/56a7cba6568fcdaaeca2ddf0b80341cfc7de6285)
[André König](mailto:andre.koenig@posteo.de) | chown: use the owner and group of a reference file and apply those values to another file Example: chown --reference=foobar.txt *.txt | 2014-08-18T12:45:43 | [754797282e2e](https://github.com/tldr-pages/tldr/commit/754797282e2e9e78345492a6d23f461d86f9c129)
[rprieto](mailto:choicesmade@gmail.com) | Move pages back into a "pages" folder | 2014-03-04T13:28:29 | [f00bf64426a7](https://github.com/tldr-pages/tldr/commit/f00bf64426a792ee3aac792f9c0aec3f8b1eaa7d)

