---
author: ['James Wait', 'Matt Sephton', 'Jeff Stein', 'Ruben Vereecken', 'Igor Shubovych', 'Dylan Rees', 'marchersimon']
date: 1631539482
title: "file, TLDR Pages"
description: "file, Determine file type."
categories: "common"
---
> More information: <https://manned.org/file>.

- Give a description of the type of the specified file. Works fine for files with no file extension:

```bash
file filename
```

- Look inside a zipped file and determine the file type(s) inside:

```bash
file -z foo.zip
```

- Allow file to work with special or device files:

```bash
file -s filename
```

- Don't stop at first file type match; keep going until the end of the file:

```bash
file -k filename
```

- Determine the mime encoding type of a file:

```bash
file -i filename
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | compgen, eval, export, file: move to common (#6508) | 2021-09-13T15:24:42 | [ac46610ce633](https://github.com/tldr-pages/tldr/commit/ac46610ce6338c5a56328c69fbe047a08d663d78)
[Matt Sephton](mailto:matt.sephton@gmail.com) | split file command as it takes different args on macOS | 2017-12-14T10:16:29 | [13aebf0c2090](https://github.com/tldr-pages/tldr/commit/13aebf0c20904d1676b1d2db8fd5346abf6fe21d)
[Jeff Stein](mailto:jstein@mitre.org) | updated the mimetime ref | 2017-02-24T08:20:37 | [85d1ab34004d](https://github.com/tldr-pages/tldr/commit/85d1ab34004db49a40b9fc74b8172deb680f714e)
[Ruben Vereecken](mailto:rubenvereecken@gmail.com) | Reformatted pages once more | 2016-01-13T12:04:46 | [967633411984](https://github.com/tldr-pages/tldr/commit/9676334119847078e5e05fec393a3fe36991dbc2)
[Igor Shubovych](mailto:igor.shubovych@gmail.com) | Merge pull request #644 from jamswat/file file: add -k and -s | 2016-01-09T10:28:54 | [ca1e589c64dc](https://github.com/tldr-pages/tldr/commit/ca1e589c64dc6cf018f1def5d9bdee100f3f0002)
[James Wait](mailto:jameswait19@gmail.com) | file: add -k and -s | 2016-01-08T10:15:59 | [803ea7df4fc1](https://github.com/tldr-pages/tldr/commit/803ea7df4fc15455d8597f407344bd457f42b3f1)
[Ruben Vereecken](mailto:rubenvereecken@gmail.com) | Formatted all pages according to guidelines. | 2016-01-08T09:38:59 | [066582e8eab5](https://github.com/tldr-pages/tldr/commit/066582e8eab57bce9861cc8d379e158d61f1cc95)
[Dylan Rees](mailto:dylanrees@protonmail.ch) | Update file.md | 2015-12-29T18:35:28 | [5d62c6374bad](https://github.com/tldr-pages/tldr/commit/5d62c6374bad858bac3501d943f109839af78c91)
[Dylan Rees](mailto:dylanrees@protonmail.ch) | Update file.md | 2015-12-29T06:33:04 | [59c349178748](https://github.com/tldr-pages/tldr/commit/59c3491787483c40bd20af5a6cb4608dbdecce1a)
[Dylan Rees](mailto:dylanrees@protonmail.ch) | Create file.md | 2015-12-29T04:47:17 | [54bd1f5ce559](https://github.com/tldr-pages/tldr/commit/54bd1f5ce55994a19fa3b40676425c564644c518)

