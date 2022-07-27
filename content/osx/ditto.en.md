---
author: ['Kyle', 'webb04', 'Marco Bonelli', 'Ruben Vereecken', 'Balázs Úr']
date: 1629747204
title: "ditto, TLDR Pages"
description: "ditto, Copy files and directories."
categories: "osx"
---
> More information: <https://ss64.com/osx/ditto.html>.

- Overwrite contents of destination directory with contents of source directory:

```bash
ditto path/to/source path/to/destination
```

- Print a line to the Terminal window for every file that's being copied:

```bash
ditto -V path/to/source path/to/destination
```

- Copy a given file or directory, while retaining the original file permissions:

```bash
ditto -rsrc path/to/source path/to/destination
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Kyle](mailto:76597257+Gitleptune@users.noreply.github.com) | a*, g*, i*, osx[a*-i*]: add more information links (#6342) | 2021-08-23T21:33:24 | [0590a21917dc](https://github.com/tldr-pages/tldr/commit/0590a21917dc981d3cc64b8094b1cffa9d0a3b78)
[Balázs Úr](mailto:balazs@urbalazs.hu) | multiple pages: change Unicode characters to ASCII (#2802) Change Unicode characters to ASCII: - non-breaking spaces (\xc2\xa0) to [...] | 2019-02-25T00:56:24 | [6956cd5348e4](https://github.com/tldr-pages/tldr/commit/6956cd5348e4f87db1586a68ab299e46f7384b63)
[Marco Bonelli](mailto:mb5.marcob@gmail.com) | Refactor: change "folder" to "directory" where needed. This commit fixes every instance in which the word "folder" is incorrectly used [...] | 2019-02-13T16:21:04 | [2599a6de483a](https://github.com/tldr-pages/tldr/commit/2599a6de483a70601ab17b29e0f18a5a8bdcaa12)
[Ruben Vereecken](mailto:rubenvereecken@gmail.com) | Fixed English tenses as reported by tldr-lint | 2016-01-16T15:12:05 | [5a26958e942c](https://github.com/tldr-pages/tldr/commit/5a26958e942c16ccf9eb1a58bfe4e410b1707e64)
[Ruben Vereecken](mailto:rubenvereecken@gmail.com) | Formatted all pages according to guidelines. | 2016-01-08T09:38:59 | [066582e8eab5](https://github.com/tldr-pages/tldr/commit/066582e8eab57bce9861cc8d379e158d61f1cc95)
[webb04](mailto:jamie.webb@warwick.ac.uk) | ditto: add page | 2016-01-03T00:29:07 | [0fdd370a27f4](https://github.com/tldr-pages/tldr/commit/0fdd370a27f4c557428b8a7ba71694061f5af786)

