---
author: ['Waldir Pimenta', 'Srinivasan R', 'rprieto', 'Marco Bonelli', 'Ruben Vereecken', 'Ian MacIntosh', 'Dario Vladović', 'Wing', 'marchersimon']
date: 1617292466
title: "rm, TLDR Pages"
description: "rm, Remove files or directories."
categories: "common"
---
> More information: <https://www.gnu.org/software/coreutils/rm>.

- Remove files from arbitrary locations:

```bash
rm path/to/file path/to/another/file
```

- Recursively remove a directory and all its subdirectories:

```bash
rm -r path/to/directory
```

- Forcibly remove a directory, without prompting for confirmation or showing error messages:

```bash
rm -rf path/to/directory
```

- Interactively remove multiple files, with a prompt before every removal:

```bash
rm -i file(s)
```

- Remove files in verbose mode, printing a message for each removed file:

```bash
rm -v path/to/directory/*
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Dario Vladović](mailto:d.vladimyr@gmail.com) | coreutils*: use short more info links (#5658) | 2021-04-01T17:54:26 | [4830093903f6](https://github.com/tldr-pages/tldr/commit/4830093903f66ccf3ebbc2ecf477286e45edac59)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | rm: add link (#5552) | 2021-03-30T09:16:08 | [62668322a827](https://github.com/tldr-pages/tldr/commit/62668322a8278797489c72f005849770fe3f51fb)
[Marco Bonelli](mailto:mb5.marcob@gmail.com) | Refactor: improve consistency of the term "directory". This commit changes the term "folder" to "directory" in every instance where [...] | 2019-02-08T20:43:24 | [ac4094e0ad70](https://github.com/tldr-pages/tldr/commit/ac4094e0ad70a6be2163b06d24b53992b93aee4f)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | rm: various tweaks for clarity; add -v (#988) * rm: various tweaks for clarity; add -v changed some descriptions and tokens to make [...] | 2016-08-08T09:08:40 | [c424e4969b9d](https://github.com/tldr-pages/tldr/commit/c424e4969b9dfd40d51c7bbe5a92dbb62477c1ad)
[Ian MacIntosh](mailto:ianjmacintosh@gmail.com) | rm: fix typo ("it's" should be "its") | 2016-03-25T19:17:25 | [5d2160f654c6](https://github.com/tldr-pages/tldr/commit/5d2160f654c63ba1bf7ef11aa50b5b2d47cfc3b9)
[Wing](mailto:steelywing@users.noreply.github.com) | Update rm.md | 2016-01-15T10:23:41 | [b5d0a4a779fb](https://github.com/tldr-pages/tldr/commit/b5d0a4a779fbb5d8f28ae0a84c00ad1ed3763ed8)
[Wing](mailto:steelywing@users.noreply.github.com) | `rm -rf` | 2016-01-14T14:43:17 | [7a30cfcf8a26](https://github.com/tldr-pages/tldr/commit/7a30cfcf8a264d95a3ac74894bedfa5903d69a63)
[Ruben Vereecken](mailto:rubenvereecken@gmail.com) | Formatted all pages according to guidelines. | 2016-01-08T09:38:59 | [066582e8eab5](https://github.com/tldr-pages/tldr/commit/066582e8eab57bce9861cc8d379e158d61f1cc95)
[Srinivasan R](mailto:srinivasanr@gmail.com) | Normalize the final new line Fixes #310 Some files had no newlines, some had 1 newline and some more than 1 newline. Normalize them [...] | 2015-10-28T09:33:06 | [e4114fa6cce7](https://github.com/tldr-pages/tldr/commit/e4114fa6cce7339425809afef817b06e872d7ca7)
[rprieto](mailto:choicesmade@gmail.com) | Move pages back into a "pages" folder | 2014-03-04T13:28:29 | [f00bf64426a7](https://github.com/tldr-pages/tldr/commit/f00bf64426a792ee3aac792f9c0aec3f8b1eaa7d)

