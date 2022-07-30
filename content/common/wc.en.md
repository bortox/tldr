---
author: ['Dario Vladović', 'Igor Shubovych', 'jassler', 'Abel', 'rprieto', 'Srinivasan R', 'Ruben Vereecken', "Kevin O'Neal", 'marchersimon']
date: 1636444089
title: "wc"
description: "wc, Count lines, words, and bytes."
categories: "common"
---
> More information: <https://www.gnu.org/software/coreutils/wc>.

- Count all lines in a file:

```bash
wc --lines path/to/file
```

- Count all words in a file:

```bash
wc --words path/to/file
```

- Count all bytes in a file:

```bash
wc --bytes path/to/file
```

- Count all characters in a file (taking multi-byte characters into account):

```bash
wc --chars path/to/file
```

- Count all lines, words and bytes from `stdin`:

```bash
find . | wc
```

- Count the length of the longest line in number of characters:

```bash
wc --max-line-length path/to/file
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | wc: refresh (#7391) | 2021-11-09T08:48:09 | [69267420f74c](https://github.com/tldr-pages/tldr/commit/69267420f74c6294a3cf0ff14160e27bb3c4ace8)
[Abel](mailto:abel.tay@gmail.com) | wc: split osx and common platform (#6834) | 2021-10-13T19:32:18 | [ba2a835251f1](https://github.com/tldr-pages/tldr/commit/ba2a835251f1027b7e8f81ac7fabbc9648a75fbc)
[Dario Vladović](mailto:d.vladimyr@gmail.com) | coreutils*: use short more info links (#5658) | 2021-04-01T17:54:26 | [4830093903f6](https://github.com/tldr-pages/tldr/commit/4830093903f66ccf3ebbc2ecf477286e45edac59)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | wc: add more information link (#5600) | 2021-03-30T15:48:08 | [4420ed005ff8](https://github.com/tldr-pages/tldr/commit/4420ed005ff8735eaf1b8932618d0c5ff2caec0e)
[jassler](mailto:erifetim@gmail.com) | wc: add pipe example (#4067) Co-authored-by: Starbeamrainbowlabs <sbrl@starbeamrainbowlabs.com> | 2020-05-29T13:01:37 | [34519ed7701f](https://github.com/tldr-pages/tldr/commit/34519ed7701fbc99fc00bdcad29268ea364ff28f)
[Kevin O'Neal](mailto:oneal.kevin@gmail.com) | wc: order count types (#3565) | 2019-11-14T17:58:45 | [5db10fff8851](https://github.com/tldr-pages/tldr/commit/5db10fff88518f6f3b612fc85b0c669b064c9378)
[Igor Shubovych](mailto:igor.shubovych@gmail.com) | wc: add words example, update characters example | 2016-02-10T18:49:07 | [4e1da9c809cd](https://github.com/tldr-pages/tldr/commit/4e1da9c809cd49281bf762a2833f131baf21af02)
[Ruben Vereecken](mailto:rubenvereecken@gmail.com) | Formatted all pages according to guidelines. | 2016-01-08T09:38:59 | [066582e8eab5](https://github.com/tldr-pages/tldr/commit/066582e8eab57bce9861cc8d379e158d61f1cc95)
[Srinivasan R](mailto:srinivasanr@gmail.com) | Normalize the final new line Fixes #310 Some files had no newlines, some had 1 newline and some more than 1 newline. Normalize them [...] | 2015-10-28T09:33:06 | [e4114fa6cce7](https://github.com/tldr-pages/tldr/commit/e4114fa6cce7339425809afef817b06e872d7ca7)
[rprieto](mailto:choicesmade@gmail.com) | Move pages back into a "pages" folder | 2014-03-04T13:28:29 | [f00bf64426a7](https://github.com/tldr-pages/tldr/commit/f00bf64426a792ee3aac792f9c0aec3f8b1eaa7d)

