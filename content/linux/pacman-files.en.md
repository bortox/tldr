---
author: ['Axel Navarro', 'Peter Babič', 'marchersimon']
date: 1620637392
title: "pacman --files"
description: "pacman --files, Arch Linux package manager utility."
categories: "linux"
---
> See also `pkgfile`.

> More information: <https://man.archlinux.org/man/pacman.8>.

- Display help:

```bash
pacman --files --help
```

- Update the package database:

```bash
sudo pacman --files --refresh
```

- Find the package that owns a specific file:

```bash
pacman --files filename
```

- Find the package that owns a specific file, using a regular expression:

```bash
pacman --files --regex 'regular_expression'
```

- List only the package names:

```bash
pacman --files --quiet filename
```

- List the files owned by a specific package:

```bash
pacman --files --list package_name
```

- List only the absolute path to the files:

```bash
pacman --query --list --quiet package_name
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | multiple pages: normalize `regular expression` instead of `regex`, `regexp` or `pattern` (#5830) | 2021-05-10T11:03:12 | [10728f1ab485](https://github.com/tldr-pages/tldr/commit/10728f1ab485957d66af3940a030b0fb77611fc0)
[Peter Babič](mailto:peter@babic.dev) | pacman-files: include see also (#5829) | 2021-04-25T14:07:10 | [5197ccd461af](https://github.com/tldr-pages/tldr/commit/5197ccd461af6c81fdc48a87c4b6ed730d1f6f2f)
[Peter Babič](mailto:peter@babic.dev) | fix identical typo in a parameter (#5794) | 2021-04-19T20:36:35 | [d3ab21c2eb45](https://github.com/tldr-pages/tldr/commit/d3ab21c2eb45801b159c818d4653f50a51624458)
[Peter Babič](mailto:peter@babic.dev) | pacman-files: fix typo (#5793) Parameter --quite is almost certainly a typo. A correct form is --quiet. This was tested before PR. | 2021-04-19T20:04:21 | [73cdbae087c5](https://github.com/tldr-pages/tldr/commit/73cdbae087c5fa13ccd854fcacf561532c250f22)
[Axel Navarro](mailto:navarroaxel@gmail.com) | pacman-files: add page (#5303) | 2021-03-08T20:02:50 | [392fd6b434d7](https://github.com/tldr-pages/tldr/commit/392fd6b434d7ae7bd583f54d196055a0ffb6f62b)

