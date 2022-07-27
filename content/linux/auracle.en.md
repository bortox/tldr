---
author: ['Hermann Mayer', 'bl-ue', 'marchersimon']
date: 1621541621
title: "auracle, TLDR Pages"
description: "auracle, Command-line tool used to interact with Arch Linux's User Repository, commonly referred to as the AUR."
categories: "linux"
---
> More information: <https://github.com/falconindy/auracle>.

- Display AUR packages that match a regular expression:

```bash
auracle search 'regular_expression'
```

- Display package information for a space-separated list of AUR packages:

```bash
auracle info package1 package2
```

- Display the `PKGBUILD` file (build information) for a space-separated list of AUR packages:

```bash
auracle show package1 package2
```

- Display updates for installed AUR packages:

```bash
auracle outdated
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | *: fix typos reported by Hunspell (#5848) Co-authored-by: marchersimon <50295997+marchersimon@users.noreply.github.com> Co-authored- [...] | 2021-05-20T22:13:41 | [8ebd171d6f00](https://github.com/tldr-pages/tldr/commit/8ebd171d6f001698709fefc02b1fd5cc9f3a99c4)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | multiple pages: normalize `regular expression` instead of `regex`, `regexp` or `pattern` (#5830) | 2021-05-10T11:03:12 | [10728f1ab485](https://github.com/tldr-pages/tldr/commit/10728f1ab485957d66af3940a030b0fb77611fc0)
[Hermann Mayer](mailto:hermann.mayer92@gmail.com) | auracle: add page, gem,bundle: update (#4572) gem: add SemVer spec install example bundle: fix update example, add patch-update, [...] | 2020-10-15T00:22:59 | [dd955ca693db](https://github.com/tldr-pages/tldr/commit/dd955ca693dbdc34c25f2541065a554ae43227b6)

