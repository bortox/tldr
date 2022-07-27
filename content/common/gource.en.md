---
author: ['Waldir Pimenta', 'Marco Bonelli', 'pxgamer', 'Fürbringer', 'Lucas Gabriel Schneider', 'Seth Falco']
date: 1629050349
title: "gource, TLDR Pages"
description: "gource, Renders an animated tree diagram of Git, SVN, Mercurial and Bazaar repositories."
categories: "common"
---
> It shows files and directories being created, modified or removed over time.

> More information: <https://gource.io>.

- Run gource in a directory (if it isn't the repository's root directory, the root is sought up from there):

```bash
gource path/to/repository
```

- Run gource in the current directory, with a custom output resolution:

```bash
gource -widthxheight
```

- Set a custom timescale for the animation:

```bash
gource -c time_scale_multiplier
```

- Set how long each day should be in the animation (this combines with -c, if provided):

```bash
gource -s seconds
```

- Set fullscreen mode and a custom background color:

```bash
gource -f -b hex_color_code
```

- Set a title for the animation:

```bash
gource --title title
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Seth Falco](mailto:seth@falco.fun) | *: fix errors reported by languagetool (#6069) | 2021-08-15T19:59:09 | [3e4c519004a4](https://github.com/tldr-pages/tldr/commit/3e4c519004a471c861cdc609fd7239ee3355671c)
[pxgamer](mailto:owzie123@gmail.com) | gource: add link to homepage | 2019-06-07T23:58:59 | [d41b0f524d73](https://github.com/tldr-pages/tldr/commit/d41b0f524d73392a2003dc0f747567f1fc58b3c8)
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | multiple pages: fixed typos (#2871) | 2019-04-06T14:34:03 | [9abddffd09d3](https://github.com/tldr-pages/tldr/commit/9abddffd09d33dba8c1e022085f7aa4e7ca6ce1b)
[Marco Bonelli](mailto:mb5.marcob@gmail.com) | Refactor: change "folder" to "directory" where needed. This commit fixes every instance in which the word "folder" is incorrectly used [...] | 2019-02-13T16:21:04 | [2599a6de483a](https://github.com/tldr-pages/tldr/commit/2599a6de483a70601ab17b29e0f18a5a8bdcaa12)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | shorten descs | 2017-01-05T05:41:07 | [8d3a48c689d4](https://github.com/tldr-pages/tldr/commit/8d3a48c689d4de7749470dd42947040301b89046)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | mention that -s and -c can be combined | 2017-01-05T05:41:07 | [6df5df53a4c4](https://github.com/tldr-pages/tldr/commit/6df5df53a4c4033fed63f929f324ffdbefe920a7)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | gource: tweak command descriptions | 2017-01-05T05:41:07 | [94f408fd480b](https://github.com/tldr-pages/tldr/commit/94f408fd480b59f0d9f7674ac370f820b2c8bc49)
[Fürbringer](mailto:severin@protonmail.ch) | gource: add page (#1211) | 2016-12-27T20:48:24 | [44051b4c1ee7](https://github.com/tldr-pages/tldr/commit/44051b4c1ee79e0ea95b79337a4705eb2bce6d1f)

