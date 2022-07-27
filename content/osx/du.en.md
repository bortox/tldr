---
author: ['Waldir Pimenta', 'lord63', 'Kyle', 'Marco Bonelli', 'Ruben Vereecken', 'Agniva De Sarker', 'rprieto', 'Axel Navarro', 'Lucas Gabriel Schneider', 'Seth Falco', 'marchersimon']
date: 1634848494
title: "du, TLDR Pages"
description: "du, Disk usage: estimate and summarize file and directory space usage."
categories: "osx"
---
> More information: <https://ss64.com/osx/du.html>.

- List the sizes of a directory and any subdirectories, in the given unit (KiB/MiB/GiB):

```bash
du -k|m|g path/to/directory
```

- List the sizes of a directory and any subdirectories, in human-readable form (i.e. auto-selecting the appropriate unit for each size):

```bash
du -h path/to/directory
```

- Show the size of a single directory, in human-readable units:

```bash
du -sh path/to/directory
```

- List the human-readable sizes of a directory and of all the files and directories within it:

```bash
du -ah path/to/directory
```

- List the human-readable sizes of a directory and any subdirectories, up to N levels deep:

```bash
du -h -d N path/to/directory
```

- List the human-readable size of all `.jpg` files in subdirectories of the current directory, and show a cumulative total at the end:

```bash
du -ch */*.jpg
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | du: fix wrong byte units (#7131) | 2021-10-21T22:34:54 | [0ddea62ffb82](https://github.com/tldr-pages/tldr/commit/0ddea62ffb822afabf0437c9a0d15258f13ce672)
[Axel Navarro](mailto:navarroaxel@gmail.com) | du: fix token syntax in example (#6851) | 2021-10-11T22:39:51 | [fe26d7e18c6a](https://github.com/tldr-pages/tldr/commit/fe26d7e18c6a3110faec6d5b2085c206cecd87f7)
[Kyle](mailto:76597257+Gitleptune@users.noreply.github.com) | a*, g*, i*, osx[a*-i*]: add more information links (#6342) | 2021-08-23T21:33:24 | [0590a21917dc](https://github.com/tldr-pages/tldr/commit/0590a21917dc981d3cc64b8094b1cffa9d0a3b78)
[Seth Falco](mailto:seth@falco.fun) | *: fix errors reported by languagetool (#6069) | 2021-08-15T19:59:09 | [3e4c519004a4](https://github.com/tldr-pages/tldr/commit/3e4c519004a471c861cdc609fd7239ee3355671c)
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | multiple pages: format technical tokens (#5119) Co-authored-by: bl-ue <54780737+bl-ue@users.noreply.github.com> Co-authored-by: [...] | 2021-01-31T18:05:18 | [a5fe31bc47ae](https://github.com/tldr-pages/tldr/commit/a5fe31bc47aece3efa5e66b52b3cf384f27d5d72)
[Marco Bonelli](mailto:mb5.marcob@gmail.com) | Refactor: change "folder" to "directory" where needed. This commit fixes every instance in which the word "folder" is incorrectly used [...] | 2019-02-13T16:21:04 | [2599a6de483a](https://github.com/tldr-pages/tldr/commit/2599a6de483a70601ab17b29e0f18a5a8bdcaa12)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | du: rework page, add glob matching example (fixes #1032) (#1034) * fixup: remove excess whitespace * du: various tweaks - improve main [...] | 2016-09-10T13:18:28 | [62d4d4816fae](https://github.com/tldr-pages/tldr/commit/62d4d4816fae935457fccd493993380d798b148a)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | osx/du.md: fix depth option, plus minor tweaks The version I have uses `-d` for the depth option, not `-depth`. Here's the version [...] | 2016-08-03T13:30:02 | [d1c342fb6ce4](https://github.com/tldr-pages/tldr/commit/d1c342fb6ce4891664093ca007bbe8f1f609ee06)
[Agniva De Sarker](mailto:agnivade@yahoo.co.in) | Applying the snake_case convention throughout the repo (#967) * Applying the snake_case convention throughout the repo - Also removing [...] | 2016-07-22T22:24:06 | [3da76e4150b8](https://github.com/tldr-pages/tldr/commit/3da76e4150b8631fd74aabfcc953cc23731b6bb8)
[Ruben Vereecken](mailto:rubenvereecken@gmail.com) | Formatted all pages according to guidelines. | 2016-01-08T09:38:59 | [066582e8eab5](https://github.com/tldr-pages/tldr/commit/066582e8eab57bce9861cc8d379e158d61f1cc95)
[lord63](mailto:lord63.j@gmail.com) | Fix lint for osx | 2015-10-22T09:33:24 | [3e1df9f818b1](https://github.com/tldr-pages/tldr/commit/3e1df9f818b1c0751b2db2379388378df85efa19)
[rprieto](mailto:choicesmade@gmail.com) | Move pages back into a "pages" folder | 2014-03-04T13:28:29 | [f00bf64426a7](https://github.com/tldr-pages/tldr/commit/f00bf64426a792ee3aac792f9c0aec3f8b1eaa7d)

