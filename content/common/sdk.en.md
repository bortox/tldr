---
author: ['Nikolay Chernov', 'Pierre Rudloff', 'Elijah Shackelford', 'pxgamer', 'Nicolas Kosinski']
date: 1633517930
title: "sdk, TLDR Pages"
description: "sdk, Tool for managing parallel versions of multiple Software Development Kits."
categories: "common"
---
> Supports Java, Groovy, Scala, Kotlin, Gradle, Maven, Vert.x and many others.

> More information: <https://sdkman.io/usage>.

- Install a specific version of Gradle:

```bash
sdk install gradle gradle_version
```

- Switch to a specific version of Gradle:

```bash
sdk use gradle gradle_version
```

- Check current Gradle version:

```bash
sdk current gradle
```

- List all Software Development Kits available to install:

```bash
sdk list
```

- List all available versions for a specific Software Development Kit:

```bash
sdk list sdk_name
```

- List all installed Software Development Kits:

```bash
sdk current
```

- Update Gradle to the latest version:

```bash
sdk upgrade gradle
```

- Uninstall a particular version of Gradle:

```bash
sdk rm gradle gradle_version
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Elijah Shackelford](mailto:33649649+eshack94@users.noreply.github.com) | sdk: add command to list version for specific sdk (#6760) | 2021-10-06T12:58:50 | [99f0783564ca](https://github.com/tldr-pages/tldr/commit/99f0783564ca5046a7cbd4f8f721a5434027cc79)
[Nicolas Kosinski](mailto:nicokosi@users.noreply.github.com) | sdk: (#6580) | 2021-09-25T08:03:05 | [ede6cb72f69a](https://github.com/tldr-pages/tldr/commit/ede6cb72f69af572c1c14ace9815fdc05f2a2b3c)
[Pierre Rudloff](mailto:contact@rudloff.pro) | sdk: fix documentation URL (#4076) | 2020-05-28T01:53:13 | [7045283fa1ee](https://github.com/tldr-pages/tldr/commit/7045283fa1ee12b15efbfdb7a94314f979bb9fdd)
[pxgamer](mailto:owzie123@gmail.com) | multiple pages: update the web link descriptions | 2019-05-29T14:41:10 | [f2b1446e6247](https://github.com/tldr-pages/tldr/commit/f2b1446e6247d3e794ee6577dee0c867dfc9af26)
[pxgamer](mailto:owzie123@gmail.com) | sdk: add link to homepage | 2019-05-29T14:41:10 | [bfec104931d4](https://github.com/tldr-pages/tldr/commit/bfec104931d467627fe286badf808cad5d155a02)
[Nikolay Chernov](mailto:mini-bfg@mail.ru) | sdk: add page (#2389) | 2018-10-05T15:13:18 | [d610a22ef2ae](https://github.com/tldr-pages/tldr/commit/d610a22ef2aec1c836a3cac2aa557668a14fc2ff)

