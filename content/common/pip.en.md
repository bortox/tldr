---
author: ['Muhammad Falak R Wani', 'Qimu Zheng', 'Azat Akhmetov', 'rprieto', 'Srinivasan R', 'Marco Bonelli', 'liuming', 'Starbeamrainbowlabs', 'Noah', 'Ruben Vereecken', 'marchersimon']
date: 1656398103
title: "pip"
description: "pip, Python package manager."
categories: "common"
---
> Some subcommands such as `pip install` have their own usage documentation.

> More information: <https://pip.pypa.io>.

- Install a package (see `pip install` for more install examples):

```bash
pip install package_name
```

- Install a package to the user's directory instead of the system-wide default location:

```bash
pip install --user package
```

- Upgrade a package:

```bash
pip install --upgrade package_name
```

- Uninstall a package:

```bash
pip uninstall package_name
```

- Save installed packages to file:

```bash
pip freeze > requirements.txt
```

- Show installed package info:

```bash
pip show package_name
```

- Install packages from a file:

```bash
pip install --requirement requirements.txt
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Muhammad Falak R Wani](mailto:falakreyaz@gmail.com) | pip: add install from requirements.txt example (#8161) | 2022-06-28T08:35:03 | [0dd0fcb430c4](https://github.com/tldr-pages/tldr/commit/0dd0fcb430c4d6ab55aa072c3f0a5aba09b70a3f)
[Noah](mailto:nbaltunian@gmail.com) | pip: synchronize long options, formatting and add --user example (#6605) | 2021-11-07T14:25:16 | [4042138a51c8](https://github.com/tldr-pages/tldr/commit/4042138a51c845a4fff7744f4c6ffc76cdc14e12)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | mention subcommands in every base page (#6383) | 2021-09-13T10:21:21 | [bd677b8b4826](https://github.com/tldr-pages/tldr/commit/bd677b8b48260e301fb99fea794f4dc1458d1562)
[Azat Akhmetov](mailto:51468504+metov@users.noreply.github.com) | pip-install: add page (#4983) | 2020-12-30T14:25:03 | [97bfd149cf83](https://github.com/tldr-pages/tldr/commit/97bfd149cf833045b97331f4258fae93c2f2f175)
[Marco Bonelli](mailto:marco@mebeim.net) | Refactor: reword English pages' links' descriptions. | 2019-06-03T14:19:41 | [66abb98ce935](https://github.com/tldr-pages/tldr/commit/66abb98ce935c0f4516bf30c4d6da72180d5a3ab)
[liuming](mailto:lium314@gmail.com) | pip: add show example (#2932) | 2019-04-18T08:02:08 | [1972f8778ff9](https://github.com/tldr-pages/tldr/commit/1972f8778ff97d0a8a39dca727dbca87c81e4f91)
[Starbeamrainbowlabs](mailto:sbrl@starbeamrainbowlabs.com) | multiple pages: fix syntax | 2019-02-03T01:28:36 | [334c0b4fa3ea](https://github.com/tldr-pages/tldr/commit/334c0b4fa3ea6f24c50d62061db9075125cc608b)
[Starbeamrainbowlabs](mailto:sbrl@starbeamrainbowlabs.com) | pip: add homepage | 2019-02-03T01:28:36 | [1b8df9432db2](https://github.com/tldr-pages/tldr/commit/1b8df9432db2740a44e9fe5c88b4968564e38a39)
[Ruben Vereecken](mailto:rubenvereecken@gmail.com) | Formatted all pages according to guidelines. | 2016-01-08T09:38:59 | [066582e8eab5](https://github.com/tldr-pages/tldr/commit/066582e8eab57bce9861cc8d379e158d61f1cc95)
[Qimu Zheng](mailto:zheng.qm@163.com) | change format of package name and version | 2015-12-28T16:00:21 | [0a1e36ddce53](https://github.com/tldr-pages/tldr/commit/0a1e36ddce53a80a30abfeab8a7f838ae65ffa9d)
[Qimu Zheng](mailto:zheng.qm@163.com) | Add tldr for installing a specific version of a python package | 2015-12-28T14:08:20 | [020d6e604869](https://github.com/tldr-pages/tldr/commit/020d6e6048699a7bda636e4a51a0ea4eaec04558)
[Srinivasan R](mailto:srinivasanr@gmail.com) | Normalize the final new line Fixes #310 Some files had no newlines, some had 1 newline and some more than 1 newline. Normalize them [...] | 2015-10-28T09:33:06 | [e4114fa6cce7](https://github.com/tldr-pages/tldr/commit/e4114fa6cce7339425809afef817b06e872d7ca7)
[rprieto](mailto:choicesmade@gmail.com) | Move pages back into a "pages" folder | 2014-03-04T13:28:29 | [f00bf64426a7](https://github.com/tldr-pages/tldr/commit/f00bf64426a792ee3aac792f9c0aec3f8b1eaa7d)

