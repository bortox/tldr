---
author: ['Srinivasan R', 'rprieto', 'Ruben Vereecken', 'Sam Tay', 'Emily Grace Seville']
date: 1660875669
title: "pbcopy"
description: "pbcopy, Copy data from stdin to the clipboard."
categories: "osx"
---
> More information: <https://ss64.com/osx/pbcopy.html>.

- Place the contents of a specific file in the clipboard:

```bash
pbcopy < path/to/file
```

- Place the results of a specific command in the clipboard:

```bash
find . -type t -name "*.png" | pbcopy
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Sam Tay](mailto:samctay@pm.me) | pbcopy: update page (#8372) * pbcopy: fix stdin/stdout mixup in description * Update pages/osx/pbcopy.md Co-authored-by: Adrien Thebo [...] | 2022-08-19T04:21:09 | [278ac3f43949](https://github.com/tldr-pages/tldr/commit/278ac3f43949f2e5226e6132611441ebcdbbd34e)
[Emily Grace Seville](mailto:emilyseville7cf@gmail.com) | osx/*: update page (#7665) | 2022-02-14T12:21:43 | [692469016e62](https://github.com/tldr-pages/tldr/commit/692469016e62d4410ec92a8f29272e447046a0d2)
[Ruben Vereecken](mailto:rubenvereecken@gmail.com) | Formatted all pages according to guidelines. | 2016-01-08T09:38:59 | [066582e8eab5](https://github.com/tldr-pages/tldr/commit/066582e8eab57bce9861cc8d379e158d61f1cc95)
[Srinivasan R](mailto:srinivasanr@gmail.com) | Normalize the final new line Fixes #310 Some files had no newlines, some had 1 newline and some more than 1 newline. Normalize them [...] | 2015-10-28T09:33:06 | [e4114fa6cce7](https://github.com/tldr-pages/tldr/commit/e4114fa6cce7339425809afef817b06e872d7ca7)
[rprieto](mailto:choicesmade@gmail.com) | Move pages back into a "pages" folder | 2014-03-04T13:28:29 | [f00bf64426a7](https://github.com/tldr-pages/tldr/commit/f00bf64426a792ee3aac792f9c0aec3f8b1eaa7d)

