---
author: ['Schneider', 'Lucas Gabriel Schneider', 'ebergeron', 'Marco Bonelli']
date: 1612112718
title: "bower"
description: "bower, A package manager optimized for front-end web development."
categories: "common"
---
> A package can be a GitHub user/repo shorthand, a Git endpoint, a URL or a registered package.

> More information: <https://bower.io/>.

- Install a project's dependencies, listed in its bower.json:

```bash
bower install
```

- Install one or more packages to the bower_components directory:

```bash
bower install package package
```

- Uninstall packages locally from the bower_components directory:

```bash
bower uninstall package package
```

- List local packages and possible updates:

```bash
bower list
```

- Display help information about a bower command:

```bash
bower help command
```

- Create a `bower.json` file for your package:

```bash
bower init
```

- Install a specific dependency version, and add it to `bower.json`:

```bash
bower install local_name=package#version --save
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | multiple pages: format technical tokens (#5119) Co-authored-by: bl-ue <54780737+bl-ue@users.noreply.github.com> Co-authored-by: [...] | 2021-01-31T18:05:18 | [a5fe31bc47ae](https://github.com/tldr-pages/tldr/commit/a5fe31bc47aece3efa5e66b52b3cf384f27d5d72)
[Marco Bonelli](mailto:marco@mebeim.net) | Refactor: reword English pages' links' descriptions. | 2019-06-03T14:19:41 | [66abb98ce935](https://github.com/tldr-pages/tldr/commit/66abb98ce935c0f4516bf30c4d6da72180d5a3ab)
[Schneider](mailto:lucas.schneider@sap.com) | bower.md: add homepage | 2019-04-12T14:41:22 | [9136ac7a63f7](https://github.com/tldr-pages/tldr/commit/9136ac7a63f7c4c7725fdb45ee6e19d35d5dc0a0)
[ebergeron](mailto:ber.emile@gmail.com) | added bower to common pages | 2016-04-04T02:09:54 | [102286e9265f](https://github.com/tldr-pages/tldr/commit/102286e9265f77287183977a66a01769e6b3bebe)

