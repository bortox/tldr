---
author: ['Guido Lena Cota', 'fejx', 'meowmeowcat']
date: 1635959386
title: "mkfile, TLDR Pages"
description: "mkfile, Create one or more empty files of any size."
categories: "osx"
---
> More information: <https://ss64.com/osx/mkfile.html>.

- Create an empty file of 15 kilobytes:

```bash
mkfile -n 15k filename
```

- Create a file of a given size and unit (bytes, KB, MB, GB):

```bash
mkfile -n sizeb|k|m|g filename
```

- Create two files of 4 megabytes each:

```bash
mkfile -n 4m first_filename second_filename
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[meowmeowcat](mailto:meowmeowcat1211@gmail.com) | osx/m*: add more information link (#7371) | 2021-11-03T18:09:46 | [1e75baed72db](https://github.com/tldr-pages/tldr/commit/1e75baed72db8bc67f7edfc001cd572f755beba5)
[fejx](mailto:florian.jhn@gmail.com) | Change all occurrences of file_name to filename (#4059) | 2020-05-22T14:31:24 | [4e1662b729ba](https://github.com/tldr-pages/tldr/commit/4e1662b729ba2bc23f7c12f606d41a86a613f8ea)
[Guido Lena Cota](mailto:guido.lenacota@gmail.com) | mkfile: add page (#2458) | 2018-10-20T13:08:04 | [2bcf312629ef](https://github.com/tldr-pages/tldr/commit/2bcf312629ef678d1eefceefca7c97840951f2a2)

