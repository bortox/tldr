---
author: ['sebastientinel', 'bl-ue', 'yair', 'Lucas Gabriel Schneider', 'Seth Falco']
date: 1630607629
title: "imgp, TLDR Pages"
description: "imgp, Command-line image resizer and rotator for JPEG and PNG images."
categories: "linux"
---
> More information: <https://github.com/jarun/imgp>.

- Convert single images and/or whole directories containing valid image formats:

```bash
imgp -x 1366x1000 path/to/directory path/to/file
```

- Scale an image by 75% and overwrite the source image to a target resolution:

```bash
imgp -x 75 -w path/to/file
```

- Rotate an image clockwise by 90 degrees:

```bash
imgp -o 90 path/to/file
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | linux/[h-k]: add more information link (#6227) | 2021-09-02T20:33:49 | [65456d0941d0](https://github.com/tldr-pages/tldr/commit/65456d0941d092a69548cae0ed6e4f4d19bfe9d2)
[Seth Falco](mailto:seth@falco.fun) | *: fix errors reported by languagetool (#6069) | 2021-08-15T19:59:09 | [3e4c519004a4](https://github.com/tldr-pages/tldr/commit/3e4c519004a471c861cdc609fd7239ee3355671c)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | *: fix typos reported by Hunspell (#5848) Co-authored-by: marchersimon <50295997+marchersimon@users.noreply.github.com> Co-authored- [...] | 2021-05-20T22:13:41 | [8ebd171d6f00](https://github.com/tldr-pages/tldr/commit/8ebd171d6f001698709fefc02b1fd5cc9f3a99c4)
[sebastientinel](mailto:sebastien.tinel@gmail.com) | multiple pages: Unify file path syntax to indicate a 'path to' (#4816) | 2020-10-28T18:19:43 | [1d32985f2f24](https://github.com/tldr-pages/tldr/commit/1d32985f2f24e5469dddc993dd7f354f79bfa128)
[yair](mailto:yair99@gmail.com) | imgp: add page (#2078) | 2018-04-29T00:52:28 | [f8fc6d714829](https://github.com/tldr-pages/tldr/commit/f8fc6d71482914fba66b96af4488f7d6d3bf1baa)

