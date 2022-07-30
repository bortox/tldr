---
author: ['Stig124', 'Lucas Gabriel Schneider', 'Seth Falco', 'Wesalius']
date: 1629050349
title: "aspell"
description: "aspell, Interactive spell checker."
categories: "linux"
---
> More information: <http://aspell.net/>.

- Spell check a single file:

```bash
aspell check path/to/file
```

- List misspelled words from standard input:

```bash
cat file | aspell list
```

- Show available dictionary languages:

```bash
aspell dicts
```

- Run aspell with a different language (takes two-letter ISO 639 language code):

```bash
aspell --lang=cs
```

- List misspelled words from standard input and ignore words from personal word list:

```bash
cat file | aspell --personal=personal-word-list.pws list
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Seth Falco](mailto:seth@falco.fun) | *: fix errors reported by languagetool (#6069) | 2021-08-15T19:59:09 | [3e4c519004a4](https://github.com/tldr-pages/tldr/commit/3e4c519004a471c861cdc609fd7239ee3355671c)
[Stig124](mailto:stigpro@outlook.fr) | linux/[a-g]: add more information link (#6076) | 2021-07-09T16:45:55 | [3697c62b5e5c](https://github.com/tldr-pages/tldr/commit/3697c62b5e5cd9bae7a99c591cb81d1ddcfbf792)
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | multiple pages: fixed typos (#2871) | 2019-04-06T14:34:03 | [9abddffd09d3](https://github.com/tldr-pages/tldr/commit/9abddffd09d33dba8c1e022085f7aa4e7ca6ce1b)
[Wesalius](mailto:Wesalius@users.noreply.github.com) | aspell: add page (#2193) | 2018-07-15T11:26:04 | [dee2a5a25da6](https://github.com/tldr-pages/tldr/commit/dee2a5a25da6b966996aa325dee9f5ca9f3a222a)

