---
author: ['Marco Bonelli', 'pxgamer', 'Owen Voke']
date: 1559564381
title: "choco upgrade, TLDR Pages"
description: "choco upgrade, Upgrade one or more packages with Chocolatey."
categories: "windows"
---
> More information: <https://chocolatey.org/docs/commands-upgrade>.

- Upgrade one or more space-separated packages:

```bash
choco upgrade package(s)
```

- Upgrade to a specific version of a package:

```bash
choco upgrade package --version version
```

- Upgrade all packages:

```bash
choco upgrade all
```

- Upgrade all except specified comma-separated packages:

```bash
choco upgrade all --except "package(s)"
```

- Confirm all prompts automatically:

```bash
choco upgrade package --yes
```

- Specify a custom source to receive packages from:

```bash
choco upgrade package --source source_url|alias
```

- Provide a username and password for authentication:

```bash
choco upgrade package --user username --password password
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Marco Bonelli](mailto:marco@mebeim.net) | Refactor: reword English pages' links' descriptions. | 2019-06-03T14:19:41 | [66abb98ce935](https://github.com/tldr-pages/tldr/commit/66abb98ce935c0f4516bf30c4d6da72180d5a3ab)
[pxgamer](mailto:owzie123@gmail.com) | choco-upgrade: add link to homepage | 2019-03-20T06:53:44 | [922904f2b984](https://github.com/tldr-pages/tldr/commit/922904f2b9849ccd06a24a59125a6287a00e157c)
[Owen Voke](mailto:owzie123@gmail.com) | choco-upgrade: add page (#2020) | 2018-03-11T07:28:05 | [fcbf05ed2004](https://github.com/tldr-pages/tldr/commit/fcbf05ed2004111ff2810e7bc644cd37e29765a4)

