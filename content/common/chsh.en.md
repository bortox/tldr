---
author: ['Emily Grace Seville', 'Agniva De Sarker', "Telmo 'Trooper", 'Like-all', 'Janek', 'lord63', 'Martin Pool', 'Ruben Vereecken', 'marchersimon']
date: 1645706554
title: "chsh"
description: "chsh, Change the user's login shell."
categories: "common"
---
> More information: <https://manned.org/chsh>.

- Change the current user's login shell interactively:

```bash
chsh
```

- Change the login shell of the current user:

```bash
chsh -s path/to/shell
```

- Change the login shell for a given user:

```bash
chsh -s path/to/shell username
```

- List available shells:

```bash
chsh --list-shells
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Martin Pool](mailto:mbp@sourcefrog.net) | chsh: Fix `chsh -s SHELL` syntax (#7801) * It's `ch -s SHELL` to change your own shell Fixes #7800 * rephrase Co-authored-by: [...] | 2022-02-24T13:42:34 | [326cc8a262cb](https://github.com/tldr-pages/tldr/commit/326cc8a262cbad579a1f1f858df768c00eb46518)
[Emily Grace Seville](mailto:emilyseville7cf@gmail.com) | chsh: page update (#7550) | 2022-02-17T05:36:58 | [72bdbb90216a](https://github.com/tldr-pages/tldr/commit/72bdbb90216a15443709dab651bf3b217abfaf75)
[Janek](mailto:27jf@pm.me) | chsh: add interactive and --list-shells examples (#6555) | 2021-09-21T19:01:49 | [c78e90ad7649](https://github.com/tldr-pages/tldr/commit/c78e90ad7649c3b7ccec27e3a38eab7d3e01fb33)
[marchersimon](mailto:marchersimon@zohomail.eu) | replace `man.archlinux.org` with `manned.org` | 2021-04-18T16:33:27 | [9abb079afb69](https://github.com/tldr-pages/tldr/commit/9abb079afb6972f3de61a30e1b3fb849ad4b68d9)
[marchersimon](mailto:marchersimon@zohomail.eu) | chsh: add link | 2021-04-18T16:33:27 | [4e04e056f91a](https://github.com/tldr-pages/tldr/commit/4e04e056f91a413edde013cae2a1bd9b30def4a7)
[Agniva De Sarker](mailto:agnivade@yahoo.co.in) | Revert "chsh: added list chells command" (#2242) | 2018-08-13T06:32:37 | [875fe63c92e5](https://github.com/tldr-pages/tldr/commit/875fe63c92e5a412c2c36c577d032c370d30e0a7)
[Telmo 'Trooper](mailto:telmo.trooper@gmail.com) | chsh: added list chells command | 2018-08-09T09:42:59 | [15c1798a154f](https://github.com/tldr-pages/tldr/commit/15c1798a154f6756f7ad9305c4fe3a2f321b5e69)
[Ruben Vereecken](mailto:rubenvereecken@gmail.com) | Formatted all pages according to guidelines. | 2016-01-08T09:38:59 | [066582e8eab5](https://github.com/tldr-pages/tldr/commit/066582e8eab57bce9861cc8d379e158d61f1cc95)
[lord63](mailto:lord63.j@gmail.com) | Fix lint for common | 2015-10-23T02:02:34 | [56a7cba6568f](https://github.com/tldr-pages/tldr/commit/56a7cba6568fcdaaeca2ddf0b80341cfc7de6285)
[Like-all](mailto:lik3a11@gmail.com) | Pages: chsh | 2014-04-28T13:40:00 | [9e731d11fb2d](https://github.com/tldr-pages/tldr/commit/9e731d11fb2dcbddc7d1c0d861638f6fd5e35a0e)

