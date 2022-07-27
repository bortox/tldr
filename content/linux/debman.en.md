---
author: ['Stig124', 'Lucas Gabriel Schneider', 'Starbeamrainbowlabs']
date: 1625841955
title: "debman, TLDR Pages"
description: "debman, Read man pages from uninstalled packages."
categories: "linux"
---
> More information: <https://manpages.debian.org/latest/debian-goodies/debman.1.html>.

- Read a man page for a command that is provided by a specified package name:

```bash
debman -p package_name command_name
```

- Specify a package version to download:

```bash
debman -p package_name=version command_name
```

- Read a man page in a `.deb` file:

```bash
debman -f path/to/filename.deb command_name
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Stig124](mailto:stigpro@outlook.fr) | linux/[a-g]: add more information link (#6076) | 2021-07-09T16:45:55 | [3697c62b5e5c](https://github.com/tldr-pages/tldr/commit/3697c62b5e5cd9bae7a99c591cb81d1ddcfbf792)
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | multiple pages: format technical tokens (#5119) Co-authored-by: bl-ue <54780737+bl-ue@users.noreply.github.com> Co-authored-by: [...] | 2021-01-31T18:05:18 | [a5fe31bc47ae](https://github.com/tldr-pages/tldr/commit/a5fe31bc47aece3efa5e66b52b3cf384f27d5d72)
[Starbeamrainbowlabs](mailto:sbrl@starbeamrainbowlabs.com) | debman: add page (#3542) | 2019-11-11T15:37:20 | [3b7fb13b9b1e](https://github.com/tldr-pages/tldr/commit/3b7fb13b9b1ed8c113f97546e24d9549b3e42f53)

