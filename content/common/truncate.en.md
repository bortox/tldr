---
author: ['Felix Yan', 'Nir Elbaz', 'bl-ue', 'Dario Vladović', 'Fazle Arefin', 'Seth Falco', 'marchersimon']
date: 1629050349
title: "truncate, TLDR Pages"
description: "truncate, Shrink or extend the size of a file to the specified size."
categories: "common"
---
> More information: <https://www.gnu.org/software/coreutils/truncate>.

- Set a size of 10 GB to an existing file, or create a new file with the specified size:

```bash
truncate --size 10G filename
```

- Extend the file size by 50 MiB, fill with holes (which reads as zero bytes):

```bash
truncate --size +50M filename
```

- Shrink the file by 2 GiB, by removing data from the end of file:

```bash
truncate --size -2G filename
```

- Empty the file's content:

```bash
truncate --size 0 filename
```

- Empty the file's content, but do not create the file if it does not exist:

```bash
truncate --no-create --size 0 filename
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Seth Falco](mailto:seth@falco.fun) | *: fix errors reported by languagetool (#6069) | 2021-08-15T19:59:09 | [3e4c519004a4](https://github.com/tldr-pages/tldr/commit/3e4c519004a471c861cdc609fd7239ee3355671c)
[Fazle Arefin](mailto:fazlearefin@users.noreply.github.com) | truncate: add example (#6038) | 2021-05-24T20:48:17 | [fc659ec734eb](https://github.com/tldr-pages/tldr/commit/fc659ec734eb30c930886ba74c582d1a9f944ada)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | *: fix typos reported by Hunspell (#5848) Co-authored-by: marchersimon <50295997+marchersimon@users.noreply.github.com> Co-authored- [...] | 2021-05-20T22:13:41 | [8ebd171d6f00](https://github.com/tldr-pages/tldr/commit/8ebd171d6f001698709fefc02b1fd5cc9f3a99c4)
[Dario Vladović](mailto:d.vladimyr@gmail.com) | coreutils*: use short more info links (#5658) | 2021-04-01T17:54:26 | [4830093903f6](https://github.com/tldr-pages/tldr/commit/4830093903f66ccf3ebbc2ecf477286e45edac59)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | truncate: add link (#5569) | 2021-03-30T09:02:27 | [fb545b6942bb](https://github.com/tldr-pages/tldr/commit/fb545b6942bb2f0cc705552cb7e77fec942a52b2)
[Nir Elbaz](mailto:nire0510@gmail.com) | Update truncate.md (#3710) * Update truncate.md Empty a file's content command, fix missing closing bracket on "Shrink the file by [...] | 2019-12-30T13:41:06 | [4e5395df2c30](https://github.com/tldr-pages/tldr/commit/4e5395df2c3059448d0af76e246af47c75e0d6c2)
[Felix Yan](mailto:felixonmars@archlinux.org) | coreutils commands: move pages to common/ folder (#2442) | 2018-10-16T19:29:50 | [72b4f22ff97b](https://github.com/tldr-pages/tldr/commit/72b4f22ff97b1890344f2af870ad3d1c89a3f0b5)

