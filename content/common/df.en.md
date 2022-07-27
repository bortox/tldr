---
author: ['Austin', 'Srinivasan R', 'Marco Bonelli', 'Ruben Vereecken', 'Agniva De Sarker', 'Dario Vladović', 'Ein Verne', 'Ivan Aracki', 'Nicolas Kosinski', 'rprieto', 'Polle Vanhoof', 'Seth Falco', 'marchersimon']
date: 1629050349
title: "df, TLDR Pages"
description: "df, Gives an overview of the filesystem disk space usage."
categories: "common"
---
> More information: <https://www.gnu.org/software/coreutils/df>.

- Display all filesystems and their disk usage:

```bash
df
```

- Display all filesystems and their disk usage in human-readable form:

```bash
df -h
```

- Display the filesystem and its disk usage containing the given file or directory:

```bash
df path/to/file_or_directory
```

- Display statistics on the number of free inodes:

```bash
df -i
```

- Display filesystems but exclude the specified types:

```bash
df -x squashfs -x tmpfs
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Seth Falco](mailto:seth@falco.fun) | *: fix errors reported by languagetool (#6069) | 2021-08-15T19:59:09 | [3e4c519004a4](https://github.com/tldr-pages/tldr/commit/3e4c519004a471c861cdc609fd7239ee3355671c)
[Nicolas Kosinski](mailto:nicokosi@yahoo.com) | atom, clear, convert, df: sync French translations with English pages (#5797) | 2021-04-20T20:15:58 | [df7770ae6b58](https://github.com/tldr-pages/tldr/commit/df7770ae6b585a043f7a797de941a1c425acc6a5)
[Dario Vladović](mailto:d.vladimyr@gmail.com) | coreutils*: use short more info links (#5658) | 2021-04-01T17:54:26 | [4830093903f6](https://github.com/tldr-pages/tldr/commit/4830093903f66ccf3ebbc2ecf477286e45edac59)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | df: add more information link (#5557) | 2021-03-30T12:23:41 | [0812ddae5287](https://github.com/tldr-pages/tldr/commit/0812ddae5287591cb1f8064bf5eb63033cadf39b)
[Austin](mailto:Hoi15A@users.noreply.github.com) | cryfs, df, dfc, fls, ipfs, duperemove, edquote, lsattr, diskutil: (#4427) consistently use "filesystem" | 2020-10-03T16:38:06 | [cfe462c57f20](https://github.com/tldr-pages/tldr/commit/cfe462c57f20c344dad34717378c442dc32cadc2)
[Ein Verne](mailto:einverne@gmail.com) | lsblk, df: add exclude examples (#4086) | 2020-06-03T15:31:47 | [346abde565a7](https://github.com/tldr-pages/tldr/commit/346abde565a7281fc56ae5643239799b7a13e2cf)
[Ivan Aracki](mailto:aracki.ivan@gmail.com) | df: add -i flag (#3268) | 2019-09-17T21:44:33 | [a4fd7a2249c5](https://github.com/tldr-pages/tldr/commit/a4fd7a2249c5ab54fd33bb38027c98b11dfd3a0d)
[Marco Bonelli](mailto:mb5.marcob@gmail.com) | Refactor: change "folder" to "directory" where needed. This commit fixes every instance in which the word "folder" is incorrectly used [...] | 2019-02-13T16:21:04 | [2599a6de483a](https://github.com/tldr-pages/tldr/commit/2599a6de483a70601ab17b29e0f18a5a8bdcaa12)
[Agniva De Sarker](mailto:agnivade@yahoo.co.in) | Using new travis token | 2018-01-18T04:25:56 | [ec85c4372313](https://github.com/tldr-pages/tldr/commit/ec85c437231377fda94ba2423023fceaaaad77b5)
[Polle Vanhoof](mailto:vanhoofpolle@gmail.com) | df: converted to snake case and small text change | 2017-11-13T16:25:47 | [654c01fcd1ba](https://github.com/tldr-pages/tldr/commit/654c01fcd1ba4f4e0205f899fff3dceb9929064f)
[Polle Vanhoof](mailto:vanhoofpolle@gmail.com) | df: add specific file/folder usecase It can often be useful to not just list all the file systems, but to figure out on which one a [...] | 2017-11-12T19:19:53 | [2dc563ae664d](https://github.com/tldr-pages/tldr/commit/2dc563ae664d41edd6a3736ceedbd7b01fe09c0d)
[Ruben Vereecken](mailto:rubenvereecken@gmail.com) | Formatted all pages according to guidelines. | 2016-01-08T09:38:59 | [066582e8eab5](https://github.com/tldr-pages/tldr/commit/066582e8eab57bce9861cc8d379e158d61f1cc95)
[Srinivasan R](mailto:srinivasanr@gmail.com) | Normalize the final new line Fixes #310 Some files had no newlines, some had 1 newline and some more than 1 newline. Normalize them [...] | 2015-10-28T09:33:06 | [e4114fa6cce7](https://github.com/tldr-pages/tldr/commit/e4114fa6cce7339425809afef817b06e872d7ca7)
[rprieto](mailto:choicesmade@gmail.com) | Move pages back into a "pages" folder | 2014-03-04T13:28:29 | [f00bf64426a7](https://github.com/tldr-pages/tldr/commit/f00bf64426a792ee3aac792f9c0aec3f8b1eaa7d)

