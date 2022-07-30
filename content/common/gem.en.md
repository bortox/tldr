---
author: ['amine hajyoussef', 'rprieto', 'lord63', 'pxgamer', 'thoemu', 'Ruben Vereecken', 'Paul Haller', 'Hermann Mayer', 'Seth Falco', 'marchersimon']
date: 1629050349
title: "gem"
description: "gem, Interact with the package manager for the Ruby programming language."
categories: "common"
---
> More information: <https://rubygems.org>.

- Search for remote gem(s) and show all available versions:

```bash
gem search regular_expression --all
```

- Install the latest version of a gem:

```bash
gem install gemname
```

- Install specific version of a gem:

```bash
gem install gemname --version 1.0.0
```

- Install the latest matching (SemVer) version of a gem:

```bash
gem install gemname --version '~> 1.0'
```

- Update a gem:

```bash
gem update gemname
```

- List all local gems:

```bash
gem list
```

- Uninstall a gem:

```bash
gem uninstall gemname
```

- Uninstall specific version of a gem:

```bash
gem uninstall gemname --version 1.0.0
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Seth Falco](mailto:seth@falco.fun) | *: fix errors reported by languagetool (#6069) | 2021-08-15T19:59:09 | [3e4c519004a4](https://github.com/tldr-pages/tldr/commit/3e4c519004a471c861cdc609fd7239ee3355671c)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | multiple pages: normalize `regular expression` instead of `regex`, `regexp` or `pattern` (#5830) | 2021-05-10T11:03:12 | [10728f1ab485](https://github.com/tldr-pages/tldr/commit/10728f1ab485957d66af3940a030b0fb77611fc0)
[Hermann Mayer](mailto:hermann.mayer92@gmail.com) | auracle: add page, gem,bundle: update (#4572) gem: add SemVer spec install example bundle: fix update example, add patch-update, [...] | 2020-10-15T00:22:59 | [dd955ca693db](https://github.com/tldr-pages/tldr/commit/dd955ca693dbdc34c25f2541065a554ae43227b6)
[thoemu](mailto:1296465+thoemu@users.noreply.github.com) | gem: add examples for searching and uninstalling (#3172) | 2019-07-05T10:52:30 | [15c07a666b6f](https://github.com/tldr-pages/tldr/commit/15c07a666b6fec156c0af26bab0e229a7ef1d0cc)
[pxgamer](mailto:owzie123@gmail.com) | gem: add link to homepage | 2019-06-07T23:58:59 | [771c28f627e3](https://github.com/tldr-pages/tldr/commit/771c28f627e3177f95eef77ee6d4f573c8d8d08a)
[Ruben Vereecken](mailto:rubenvereecken@gmail.com) | Formatted all pages according to guidelines. | 2016-01-08T09:38:59 | [066582e8eab5](https://github.com/tldr-pages/tldr/commit/066582e8eab57bce9861cc8d379e158d61f1cc95)
[amine hajyoussef](mailto:hajyoussef.amine@gmail.com) | fix markup | 2015-12-31T13:28:12 | [7d60083f20af](https://github.com/tldr-pages/tldr/commit/7d60083f20af4c79f5dd84c200c77f3b24eafaee)
[Paul Haller](mailto:haller.paul@gmail.com) | Fixed tldr for gem Specific version instruction missed gem name and mixed up -v and --version | 2015-12-30T22:01:40 | [9da8263cfdf3](https://github.com/tldr-pages/tldr/commit/9da8263cfdf3125e7f8ed1eea7d2490f6be3e212)
[lord63](mailto:lord63.j@gmail.com) | Fix lint for common | 2015-10-23T02:02:34 | [56a7cba6568f](https://github.com/tldr-pages/tldr/commit/56a7cba6568fcdaaeca2ddf0b80341cfc7de6285)
[rprieto](mailto:choicesmade@gmail.com) | Move pages back into a "pages" folder | 2014-03-04T13:28:29 | [f00bf64426a7](https://github.com/tldr-pages/tldr/commit/f00bf64426a792ee3aac792f9c0aec3f8b1eaa7d)

