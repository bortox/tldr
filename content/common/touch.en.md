---
author: ['Peter Tripp', 'Amine Hajyoussef', 'lord63', 'Ruben Vereecken', 'Alex Day', 'blalyasar', 'Gonzalo Contreras Aso', 'Dario Vladović', 'rprieto', 'marchersimon']
date: 1635529409
title: "touch, TLDR Pages"
description: "touch, Change a file access and modification times (atime, mtime)."
categories: "common"
---
> More information: <https://www.gnu.org/software/coreutils/touch>.

- Create a new empty file(s) or change the times for existing file(s) to current time:

```bash
touch path/to/file
```

- Set the times on a file to a specific date and time:

```bash
touch -t YYYYMMDDHHMM.SS path/to/file
```

- Set the time on a file to one hour in the past:

```bash
touch -d "-1 hour" path/to/file
```

- Use the times from a file to set the times on a second file:

```bash
touch -r path/to/file1 path/to/file2
```

- Create multiple files:

```bash
touch path/to/file{1,2,3}.txt
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Alex Day](mailto:AlexanderDavid@users.noreply.github.com) | touch: add -d example (#7274) | 2021-10-29T19:43:29 | [4f922202b048](https://github.com/tldr-pages/tldr/commit/4f922202b048529215b70025b2fd13058ebff049)
[blalyasar](mailto:49458946+blalyasar@users.noreply.github.com) | ls, touch: add examples (#5855) | 2021-05-14T02:40:50 | [40e478add979](https://github.com/tldr-pages/tldr/commit/40e478add979658bc5956988739dc62218235f3f)
[Dario Vladović](mailto:d.vladimyr@gmail.com) | coreutils*: use short more info links (#5658) | 2021-04-01T17:54:26 | [4830093903f6](https://github.com/tldr-pages/tldr/commit/4830093903f66ccf3ebbc2ecf477286e45edac59)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | touch: change link (#5550) | 2021-03-30T09:15:08 | [64814bb7bac0](https://github.com/tldr-pages/tldr/commit/64814bb7bac00f937c245a550a19dc2c4b62d14f)
[Gonzalo Contreras Aso](mailto:61254163+goznalo-git@users.noreply.github.com) | mkdir, touch, nmap: add Spanish translations (#5491) | 2021-03-23T19:19:37 | [5607caaea147](https://github.com/tldr-pages/tldr/commit/5607caaea1477cb5f793e320d755b0ddd5dfb2c1)
[Peter Tripp](mailto:petertripp@gmail.com) | touch: Remove hard coded date example. Reorder wording for -r. | 2016-01-20T12:44:25 | [93b96be95cf6](https://github.com/tldr-pages/tldr/commit/93b96be95cf67044844f0ccd9f0e2b98f289455b)
[Ruben Vereecken](mailto:rubenvereecken@gmail.com) | Formatted all pages according to guidelines. | 2016-01-08T09:38:59 | [066582e8eab5](https://github.com/tldr-pages/tldr/commit/066582e8eab57bce9861cc8d379e158d61f1cc95)
[Amine Hajyoussef](mailto:hajyoussef.amine@gmail.com) | consistent markup | 2015-12-31T14:11:18 | [3fe8681e19ac](https://github.com/tldr-pages/tldr/commit/3fe8681e19acf79351509fb46b1988a0ab64397f)
[lord63](mailto:lord63.j@gmail.com) | Fix lint for common | 2015-10-23T02:02:34 | [56a7cba6568f](https://github.com/tldr-pages/tldr/commit/56a7cba6568fcdaaeca2ddf0b80341cfc7de6285)
[rprieto](mailto:choicesmade@gmail.com) | Move pages back into a "pages" folder | 2014-03-04T13:28:29 | [f00bf64426a7](https://github.com/tldr-pages/tldr/commit/f00bf64426a792ee3aac792f9c0aec3f8b1eaa7d)

