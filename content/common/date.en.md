---
author: ['P_Q_H', 'Felix Yan', 'Srinivasan R', 'Ruben Vereecken', 'Daniel Compton', 'Dario Vladović', 'Alexander Berezovsky', 'indigane', 'Ben Ripkens', 'rprieto', 'Mikey Garcia', 'bl-ue', 'marchersimon']
date: 1637961353
title: "date, TLDR Pages"
description: "date, Set or display the system date."
categories: "common"
---
> More information: <https://www.gnu.org/software/coreutils/date>.

- Display the current date using the default locale's format:

```bash
date +"%c"
```

- Display the current date in UTC and ISO 8601 format:

```bash
date -u +"%Y-%m-%dT%H:%M:%SZ"
```

- Display the current date as a Unix timestamp (seconds since the Unix epoch):

```bash
date +%s
```

- Display a specific date (represented as a Unix timestamp) using the default format:

```bash
date -d @1473305798
```

- Convert a specific date to the Unix timestamp format:

```bash
date -d "2018-09-01 00:00" +%s --utc
```

- Display the current date using the RFC-3339 format (`YYYY-MM-DD hh:mm:ss TZ`):

```bash
date --rfc-3339=s
```

- Set the current date using the format `MMDDhhmmYYYY.ss` (`YYYY` and `.ss` are optional):

```bash
date 093023592021.59
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[indigane](mailto:indigane@users.noreply.github.com) | date: add set date (#7019) | 2021-11-26T22:15:53 | [9c8a7b66852f](https://github.com/tldr-pages/tldr/commit/9c8a7b66852f00598233d1dfac33aa1d2a77db93)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | Revert "date: fix typo (#4069)" (#5997) | 2021-05-20T18:36:10 | [33b5fcd7bdc9](https://github.com/tldr-pages/tldr/commit/33b5fcd7bdc9e3e169e3a3c5c8b767dcb05b770e)
[Dario Vladović](mailto:d.vladimyr@gmail.com) | coreutils*: use short more info links (#5658) | 2021-04-01T17:54:26 | [4830093903f6](https://github.com/tldr-pages/tldr/commit/4830093903f66ccf3ebbc2ecf477286e45edac59)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | date: add more information link (#5603) | 2021-03-30T15:50:57 | [b98c0e84a5b2](https://github.com/tldr-pages/tldr/commit/b98c0e84a5b2228add4fe1831fd2eb151c14bca1)
[Mikey Garcia](mailto:gikeymarcia@gmail.com) | date: fix typo (#4069) | 2020-05-27T05:46:20 | [e0151803205b](https://github.com/tldr-pages/tldr/commit/e0151803205bb7efa1e2222a979580dbcfc19589)
[Alexander Berezovsky](mailto:a-b@users.noreply.github.com) | Add date RFC 3339 (#3902) | 2020-03-28T02:47:55 | [d48c39ee932e](https://github.com/tldr-pages/tldr/commit/d48c39ee932e3bafd8bc00a5fddc6044e34b0717)
[P_Q_H](mailto:keatingsmitht@gmail.com) | date: convert specific date to timestamp (#2697) | 2019-01-11T11:12:29 | [6fea929b1498](https://github.com/tldr-pages/tldr/commit/6fea929b1498854ea478fdaddacb5ecc982a5e76)
[Felix Yan](mailto:felixonmars@archlinux.org) | coreutils commands: move pages to common/ folder (#2442) | 2018-10-16T19:29:50 | [72b4f22ff97b](https://github.com/tldr-pages/tldr/commit/72b4f22ff97b1890344f2af870ad3d1c89a3f0b5)
[Daniel Compton](mailto:desk@danielcompton.net) | Add unix epoch commands These differ between Linux and OS X so the pages needed to be split. | 2016-09-08T13:00:50 | [8136ac19301b](https://github.com/tldr-pages/tldr/commit/8136ac19301be22a68a91ef60a1bd867cca4cd6c)
[Ruben Vereecken](mailto:rubenvereecken@gmail.com) | Formatted all pages according to guidelines. | 2016-01-08T09:38:59 | [066582e8eab5](https://github.com/tldr-pages/tldr/commit/066582e8eab57bce9861cc8d379e158d61f1cc95)
[Ben Ripkens](mailto:bripkens.dev@gmail.com) | Retrieve ISO 8601 date via date utility | 2015-12-06T17:42:23 | [96d7c1752d5b](https://github.com/tldr-pages/tldr/commit/96d7c1752d5b259e6d0c39eed03aa3d88800aecc)
[Srinivasan R](mailto:srinivasanr@gmail.com) | Normalize the final new line Fixes #310 Some files had no newlines, some had 1 newline and some more than 1 newline. Normalize them [...] | 2015-10-28T09:33:06 | [e4114fa6cce7](https://github.com/tldr-pages/tldr/commit/e4114fa6cce7339425809afef817b06e872d7ca7)
[rprieto](mailto:choicesmade@gmail.com) | Move pages back into a "pages" folder | 2014-03-04T13:28:29 | [f00bf64426a7](https://github.com/tldr-pages/tldr/commit/f00bf64426a792ee3aac792f9c0aec3f8b1eaa7d)

