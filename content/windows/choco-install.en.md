---
author: ['Owen Voke', 'pxgamer', 'Lucas Gabriel Schneider', 'Marco Bonelli']
date: 1612112718
title: "choco install"
description: "choco install, Install one or more packages with Chocolatey."
categories: "windows"
---
> More information: <https://chocolatey.org/docs/commands-install>.

- Install one or more space-separated packages:

```bash
choco install package(s)
```

- Install packages from a custom configuration file:

```bash
choco install path/to/packages.config
```

- Install a specific nuspec or nupkg file:

```bash
choco install path/to/file
```

- Install a specific version of a package:

```bash
choco install package --version version
```

- Allow installing multiple versions of a package:

```bash
choco install package --allow-multiple
```

- Confirm all prompts automatically:

```bash
choco install package --yes
```

- Specify a custom source to receive packages from:

```bash
choco install package --source source_url|alias
```

- Provide a username and password for authentication:

```bash
choco install package --user username --password password
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | multiple pages: format technical tokens (#5119) Co-authored-by: bl-ue <54780737+bl-ue@users.noreply.github.com> Co-authored-by: [...] | 2021-01-31T18:05:18 | [a5fe31bc47ae](https://github.com/tldr-pages/tldr/commit/a5fe31bc47aece3efa5e66b52b3cf384f27d5d72)
[Marco Bonelli](mailto:marco@mebeim.net) | Refactor: reword English pages' links' descriptions. | 2019-06-03T14:19:41 | [66abb98ce935](https://github.com/tldr-pages/tldr/commit/66abb98ce935c0f4516bf30c4d6da72180d5a3ab)
[pxgamer](mailto:owzie123@gmail.com) | choco-install: add link to homepage | 2019-03-20T06:53:44 | [a77f64235d65](https://github.com/tldr-pages/tldr/commit/a77f64235d659ba38b7dbd78b256b21a9e06224f)
[Owen Voke](mailto:owzie123@gmail.com) | choco-install: add page (#2017) | 2018-03-08T23:42:32 | [acfa4687933d](https://github.com/tldr-pages/tldr/commit/acfa4687933d7fb70cbe9adbaef1f46ac446808e)

