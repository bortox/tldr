---
author: ['Waldir Pimenta', 'Dario Vladović', 'Igor Shubovych', 'Denis Sokolov', 'Agniva De Sarker', 'Juri Hahn', 'rprieto', 'Andreas Simon', 'Marco Bonelli', 'Ruben Vereecken', 'marchersimon']
date: 1622748014
title: "ln"
description: "ln, Creates links to files and directories."
categories: "common"
---
> More information: <https://www.gnu.org/software/coreutils/ln>.

- Create a symbolic link to a file or directory:

```bash
ln -s /path/to/file_or_directory path/to/symlink
```

- Overwrite an existing symbolic link to point to a different file:

```bash
ln -sf /path/to/new_file path/to/symlink
```

- Create a hard link to a file:

```bash
ln /path/to/file path/to/hardlink
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[marchersimon](mailto:marchersimon@zohomail.eu) | ln: convert paths to absolute | 2021-06-03T21:20:14 | [0deb4d0597d4](https://github.com/tldr-pages/tldr/commit/0deb4d0597d4eab6abd597fb83e20eb396cf1435)
[Dario Vladović](mailto:d.vladimyr@gmail.com) | coreutils*: use short more info links (#5658) | 2021-04-01T17:54:26 | [4830093903f6](https://github.com/tldr-pages/tldr/commit/4830093903f66ccf3ebbc2ecf477286e45edac59)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | ln: add more information link (#5560) | 2021-03-30T12:33:54 | [cd1189ec96ca](https://github.com/tldr-pages/tldr/commit/cd1189ec96caf2faa1056e696b0375f341999629)
[Juri Hahn](mailto:juhah@web.de) | ln: add missing noun (#4883) | 2020-10-28T14:28:52 | [1a6fb76e54c2](https://github.com/tldr-pages/tldr/commit/1a6fb76e54c202c6f8237bb258dea12f00c3d84d)
[Marco Bonelli](mailto:mb5.marcob@gmail.com) | Refactor: change "folder" to "directory" where needed. This commit fixes every instance in which the word "folder" is incorrectly used [...] | 2019-02-13T16:21:04 | [2599a6de483a](https://github.com/tldr-pages/tldr/commit/2599a6de483a70601ab17b29e0f18a5a8bdcaa12)
[Marco Bonelli](mailto:mb5.marcob@gmail.com) | Refactor: add missing `or_directory` where needed. This commit adds the missing `_or_directory` to any example which is specifying an [...] | 2019-02-08T20:43:24 | [f79f6011e0f2](https://github.com/tldr-pages/tldr/commit/f79f6011e0f298311848b5f38d66c309d4b92665)
[Agniva De Sarker](mailto:agnivade@yahoo.co.in) | Applying the snake_case convention throughout the repo (#967) * Applying the snake_case convention throughout the repo - Also removing [...] | 2016-07-22T22:24:06 | [3da76e4150b8](https://github.com/tldr-pages/tldr/commit/3da76e4150b8631fd74aabfcc953cc23731b6bb8)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | without the dir example, "file" is redundant here | 2016-01-22T02:00:04 | [d3b8b8e51aed](https://github.com/tldr-pages/tldr/commit/d3b8b8e51aed9e79feec98b2e8a8742c20da02da)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | reword to prevent ambiguity "original" can be associated with the origin of the link and lead to confusion if not read carefully. [...] | 2016-01-22T01:56:04 | [dff2a308ace6](https://github.com/tldr-pages/tldr/commit/dff2a308ace6f6f6ce4a743ee09c24b303b0cb6c)
[Ruben Vereecken](mailto:rubenvereecken@gmail.com) | Formatted all pages according to guidelines. | 2016-01-08T09:38:59 | [066582e8eab5](https://github.com/tldr-pages/tldr/commit/066582e8eab57bce9861cc8d379e158d61f1cc95)
[Igor Shubovych](mailto:igor.shubovych@gmail.com) | Merge branch 'patch-6' of git://github.com/denis-sokolov/tldr into denis-sokolov-patch-6 | 2016-01-06T11:33:47 | [1b63a9d58c1d](https://github.com/tldr-pages/tldr/commit/1b63a9d58c1dd8643e8b71d156d342dd9065e63e)
[Denis Sokolov](mailto:denis@sokolov.cc) | ln: remove overwrite option for directories -T is not present on my system, and the behavior itself is completely unintuitive. How [...] | 2016-01-05T22:18:49 | [5554a6d2a430](https://github.com/tldr-pages/tldr/commit/5554a6d2a430f13130d6f9e5747540e9cb4c41ad)
[Denis Sokolov](mailto:denis@sokolov.cc) | ln: remove note about hard links for directories Hard links are generally not allowed for directories. | 2016-01-05T21:31:52 | [5c694e6f9c61](https://github.com/tldr-pages/tldr/commit/5c694e6f9c61bf98c7065edaaa843350eed588a6)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | add a separate example for overwriting a symlink to make it clear what the -T option does, as discussed in #180 | 2015-03-15T12:40:20 | [0d0180c172a1](https://github.com/tldr-pages/tldr/commit/0d0180c172a144e731739637b9be8c8f28fba5a1)
[Andreas Simon](mailto:github@andreas-simon.info) | Added example of overwriting an existing link | 2014-04-01T10:47:34 | [0b8d32a1a8cf](https://github.com/tldr-pages/tldr/commit/0b8d32a1a8cf9919d726655d5bd4d2c539ee006c)
[rprieto](mailto:choicesmade@gmail.com) | Move pages back into a "pages" folder | 2014-03-04T13:28:29 | [f00bf64426a7](https://github.com/tldr-pages/tldr/commit/f00bf64426a792ee3aac792f9c0aec3f8b1eaa7d)

