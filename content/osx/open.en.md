---
author: ['Robbie S', 'Daniel Bayley', 'Srinivasan R', 'Emily Grace Seville', 'Ruben Vereecken', 'Diogo Pinela', 'Agniva De Sarker', 'rprieto']
date: 1644837703
title: "open, TLDR Pages"
description: "open, Opens files, directories and applications."
categories: "osx"
---
> More information: <https://ss64.com/osx/open.html>.

- Open a file with the associated application:

```bash
open file.ext
```

- Run a graphical macOS application:

```bash
open -a "Application"
```

- Run a graphical macOS app based on the bundle identifier (refer to `osascript` for an easy way to get this):

```bash
open -b com.domain.application
```

- Open the current directory in Finder:

```bash
open .
```

- Reveal a file in Finder:

```bash
open -R path/to/file
```

- Open all the files of a given extension in the current directory with the associated application:

```bash
open *.ext
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Emily Grace Seville](mailto:emilyseville7cf@gmail.com) | osx/*: update page (#7665) | 2022-02-14T12:21:43 | [692469016e62](https://github.com/tldr-pages/tldr/commit/692469016e62d4410ec92a8f29272e447046a0d2)
[Diogo Pinela](mailto:diogoid7400@gmail.com) | open: improve grammar (#3397) | 2019-10-12T23:32:00 | [472516a4be66](https://github.com/tldr-pages/tldr/commit/472516a4be66623244112964f67bba8f0c382f45)
[Agniva De Sarker](mailto:agnivade@yahoo.co.in) | Wrap osascript within backticks To allow clients to pick up the text as another command and allow the link to the page to be shown. | 2017-08-06T07:30:26 | [c3d824541b4d](https://github.com/tldr-pages/tldr/commit/c3d824541b4d1cf8b8cd4c272576c54156daacf9)
[Daniel Bayley](mailto:daniel.bayley@me.com) | Improve open command | 2017-08-05T20:05:52 | [3413be7258c0](https://github.com/tldr-pages/tldr/commit/3413be7258c098dd439653c014d3a048f847474a)
[Agniva De Sarker](mailto:agnivade@yahoo.co.in) | Apply the 'path/to/item' convention uniformly (#947) | 2016-07-13T10:53:22 | [fa8b2d8f92ab](https://github.com/tldr-pages/tldr/commit/fa8b2d8f92abfcbea46036b8a30c129ac53abdcb)
[Ruben Vereecken](mailto:rubenvereecken@gmail.com) | Formatted all pages according to guidelines. | 2016-01-08T09:38:59 | [066582e8eab5](https://github.com/tldr-pages/tldr/commit/066582e8eab57bce9861cc8d379e158d61f1cc95)
[Robbie S](mailto:robbie@selwynsoftware.com) | Fixed open.md | 2015-12-30T03:38:51 | [4ddaf350f25b](https://github.com/tldr-pages/tldr/commit/4ddaf350f25be1fc2be72e4281b9ffc262b1a666)
[Srinivasan R](mailto:srinivasanr@gmail.com) | Normalize the final new line Fixes #310 Some files had no newlines, some had 1 newline and some more than 1 newline. Normalize them [...] | 2015-10-28T09:33:06 | [e4114fa6cce7](https://github.com/tldr-pages/tldr/commit/e4114fa6cce7339425809afef817b06e872d7ca7)
[rprieto](mailto:choicesmade@gmail.com) | Move pages back into a "pages" folder | 2014-03-04T13:28:29 | [f00bf64426a7](https://github.com/tldr-pages/tldr/commit/f00bf64426a792ee3aac792f9c0aec3f8b1eaa7d)

