---
author: ['Luat Hoang', 'lord63', 'Andrik Albuquerque', 'Schneider', 'Marco Bonelli', 'Ruben Vereecken', 'Daniel Senff', 'Hermann Mayer', 'bl-ue']
date: 1618409562
title: "bundle, TLDR Pages"
description: "bundle, Dependency manager for the Ruby programming language."
categories: "common"
---
> More information: <https://bundler.io/man/bundle.1.html>.

- Install all gems defined in the `Gemfile` expected in the working directory:

```bash
bundle install
```

- Execute a command in the context of the current bundle:

```bash
bundle exec command arguments
```

- Update all gems by the rules defined in the `Gemfile` and regenerate `Gemfile.lock`:

```bash
bundle update
```

- Update one or more specific gem(s) defined in the `Gemfile`:

```bash
bundle update gem_name gem_name
```

- Update one or more specific gems(s) defined in the `Gemfile` but only to the next patch version:

```bash
bundle update --patch gem_name gem_name
```

- Update all gems within the given group in the `Gemfile`:

```bash
bundle update --group development
```

- List installed gems in the `Gemfile` with newer versions available:

```bash
bundle outdated
```

- Create a new gem skeleton:

```bash
bundle gem gem_name
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | bundle, mocp: fix typo (#5748) | 2021-04-14T16:12:42 | [d84f31d7db9e](https://github.com/tldr-pages/tldr/commit/d84f31d7db9e5f3131a822bcfc665e4af126d05c)
[Luat Hoang](mailto:luat.hoangn@gmail.com) | bundle: add exec example (#4995) | 2020-11-30T12:54:18 | [96f5f2049816](https://github.com/tldr-pages/tldr/commit/96f5f2049816dbea98e89beaf92d0873f2a49a51)
[Hermann Mayer](mailto:hermann.mayer92@gmail.com) | auracle: add page, gem,bundle: update (#4572) gem: add SemVer spec install example bundle: fix update example, add patch-update, [...] | 2020-10-15T00:22:59 | [dd955ca693db](https://github.com/tldr-pages/tldr/commit/dd955ca693dbdc34c25f2541065a554ae43227b6)
[Marco Bonelli](mailto:marco@mebeim.net) | Refactor: reword English pages' links' descriptions. | 2019-06-03T14:19:41 | [66abb98ce935](https://github.com/tldr-pages/tldr/commit/66abb98ce935c0f4516bf30c4d6da72180d5a3ab)
[Schneider](mailto:lucas.schneider@sap.com) | bundle.md: add homepage | 2019-04-12T14:41:22 | [5ab8b1611746](https://github.com/tldr-pages/tldr/commit/5ab8b161174640f65836b1df9d1fe6af756bbb90)
[Andrik Albuquerque](mailto:andrik.albuquerque@gmail.com) | bundle: add backticks to Gemfile and Gemfile.lock (#2894) | 2019-04-11T22:18:15 | [07eb3d7d9cc7](https://github.com/tldr-pages/tldr/commit/07eb3d7d9cc72dc5d398ee67cd79ca6efa38777a)
[Ruben Vereecken](mailto:rubenvereecken@gmail.com) | Fixed English tenses as reported by tldr-lint | 2016-01-16T15:12:05 | [5a26958e942c](https://github.com/tldr-pages/tldr/commit/5a26958e942c16ccf9eb1a58bfe4e410b1707e64)
[Ruben Vereecken](mailto:rubenvereecken@gmail.com) | Formatted all pages according to guidelines. | 2016-01-08T09:38:59 | [066582e8eab5](https://github.com/tldr-pages/tldr/commit/066582e8eab57bce9861cc8d379e158d61f1cc95)
[lord63](mailto:lord63.j@gmail.com) | Fix lint for common | 2015-10-23T02:02:34 | [56a7cba6568f](https://github.com/tldr-pages/tldr/commit/56a7cba6568fcdaaeca2ddf0b80341cfc7de6285)
[Daniel Senff](mailto:mail@danielsenff.de) | Update and rename bundler.md to bundle.md rename to bundle.md which is the more common name remove {{}} syntax from comments | 2014-09-16T17:33:44 | [cba683540a17](https://github.com/tldr-pages/tldr/commit/cba683540a17a23eb26f7cdf82c09e765e4629bd)

