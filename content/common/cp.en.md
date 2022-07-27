---
author: ['Arun Isaac', 'Waldir Pimenta', 'lord63', 'Marco Bonelli', 'FantasyCookie17', 'yurai007', 'Christian Rackerseder', 'Agniva De Sarker', 'Ruben Vereecken', 'Danny Kim', 'Dario Vladović', 'rprieto', 'marchersimon', 'Bo-Yi Wu']
date: 1619557362
title: "cp, TLDR Pages"
description: "cp, Copy files and directories."
categories: "common"
---
> More information: <https://www.gnu.org/software/coreutils/cp>.

- Copy a file to another location:

```bash
cp path/to/source_file.ext path/to/target_file.ext
```

- Copy a file into another directory, keeping the filename:

```bash
cp path/to/source_file.ext path/to/target_parent_directory
```

- Recursively copy a directory's contents to another location (if the destination exists, the directory is copied inside it):

```bash
cp -R path/to/source_directory path/to/target_directory
```

- Copy a directory recursively, in verbose mode (shows files as they are copied):

```bash
cp -vR path/to/source_directory path/to/target_directory
```

- Copy text files to another location, in interactive mode (prompts user before overwriting):

```bash
cp -i *.txt path/to/target_directory
```

- Follow symbolic links before copying:

```bash
cp -L link path/to/target_directory
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[FantasyCookie17](mailto:fantasycookie17@artemislena.eu) | cp: change 'dereference' to 'follow' (#5843) | 2021-04-27T23:02:42 | [3595c42ccefe](https://github.com/tldr-pages/tldr/commit/3595c42ccefe16488cee36507de3ebd62365addf)
[Dario Vladović](mailto:d.vladimyr@gmail.com) | coreutils*: use short more info links (#5658) | 2021-04-01T17:54:26 | [4830093903f6](https://github.com/tldr-pages/tldr/commit/4830093903f66ccf3ebbc2ecf477286e45edac59)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | cp: add more information link (#5556) | 2021-03-30T12:30:03 | [ad46ebe87a57](https://github.com/tldr-pages/tldr/commit/ad46ebe87a578bcb5e61d26addcf1bdfe287d75f)
[Danny Kim](mailto:DanielKim1@users.noreply.github.com) | cp: replace ambiguous text (#4223) | 2020-07-25T11:19:46 | [ba92cdcc4b2b](https://github.com/tldr-pages/tldr/commit/ba92cdcc4b2b19da23ee7e9c9d581fb8d36bb127)
[Christian Rackerseder](mailto:git@echooff.de) | cp: replace -r with -R (#4141) | 2020-07-06T20:30:29 | [d7fc46261350](https://github.com/tldr-pages/tldr/commit/d7fc4626135090e66d3a0f70017c852307ca8730)
[yurai007](mailto:dawid_jurek@vp.pl) | cp: add examples for common -L and Linux specific --parents (#4026) (#4026) | 2020-05-13T01:54:45 | [7b3a9b20ace2](https://github.com/tldr-pages/tldr/commit/7b3a9b20ace2f2d19cf610c932bafc056c879fb4)
[Marco Bonelli](mailto:mebeim@users.noreply.github.com) | cp: clarify and condense similar examples (#2926) | 2019-04-19T02:54:58 | [7047a2f90b92](https://github.com/tldr-pages/tldr/commit/7047a2f90b92cdc819d7d01bea27a81a66e5e830)
[Marco Bonelli](mailto:mb5.marcob@gmail.com) | Refactor: change "folder" to "directory" where needed. This commit fixes every instance in which the word "folder" is incorrectly used [...] | 2019-02-13T16:21:04 | [2599a6de483a](https://github.com/tldr-pages/tldr/commit/2599a6de483a70601ab17b29e0f18a5a8bdcaa12)
[Arun Isaac](mailto:arunisaac@users.noreply.github.com) | cp: fix typo in target folder path (#2492) | 2018-10-28T10:59:03 | [c049a605b595](https://github.com/tldr-pages/tldr/commit/c049a605b59503c65b3f1f37e7e774c03d53f928)
[Arun Isaac](mailto:arunisaac@users.noreply.github.com) | cp: remove redundant example (#2486) | 2018-10-24T21:03:20 | [eb80fc01fcca](https://github.com/tldr-pages/tldr/commit/eb80fc01fccaa7174e1f97e2f6f324a7534ece81)
[Agniva De Sarker](mailto:agnivade@yahoo.co.in) | cp: fix travis error | 2017-04-19T11:20:18 | [9fd6e9cf1187](https://github.com/tldr-pages/tldr/commit/9fd6e9cf1187fc7097b8ba24260de525a93ecdc3)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | cp: phrase -i option the same way as the -v option | 2017-04-19T11:20:18 | [c3d4b4ac553d](https://github.com/tldr-pages/tldr/commit/c3d4b4ac553d790f836716288237c817fbd71a11)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | cp: remove leading / from paths; add -i example | 2017-04-19T11:20:18 | [faed93cbae21](https://github.com/tldr-pages/tldr/commit/faed93cbae21a303ac6fbd2025a49fb4ed45eb37)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | cp: remove shell expansion examples, add -r | 2017-04-19T11:20:18 | [00656cd8c405](https://github.com/tldr-pages/tldr/commit/00656cd8c40521e3ef0221e271d029379229f14f)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | cp.md: major overhaul - change "directory" to "folder" (more beginner-friendly) - use an extension to distinguish file paths from [...] | 2017-04-19T11:20:18 | [da10202a3dbd](https://github.com/tldr-pages/tldr/commit/da10202a3dbdafe6ae9e3b6f0f03f355b208c41d)
[Ruben Vereecken](mailto:rubenvereecken@gmail.com) | Formatted all pages according to guidelines. | 2016-01-08T09:38:59 | [066582e8eab5](https://github.com/tldr-pages/tldr/commit/066582e8eab57bce9861cc8d379e158d61f1cc95)
[Bo-Yi Wu](mailto:appleboy.tw@gmail.com) | Fix file format for cp command. ref: #402 Signed-off-by: Bo-Yi Wu <appleboy.tw@gmail.com> | 2015-12-29T08:11:05 | [c431dffe85f1](https://github.com/tldr-pages/tldr/commit/c431dffe85f176e4ca9e6ba796e5a419bfadbf77)
[lord63](mailto:lord63.j@gmail.com) | Fix lint for common | 2015-10-23T02:02:34 | [56a7cba6568f](https://github.com/tldr-pages/tldr/commit/56a7cba6568fcdaaeca2ddf0b80341cfc7de6285)
[rprieto](mailto:choicesmade@gmail.com) | Move pages back into a "pages" folder | 2014-03-04T13:28:29 | [f00bf64426a7](https://github.com/tldr-pages/tldr/commit/f00bf64426a792ee3aac792f9c0aec3f8b1eaa7d)

