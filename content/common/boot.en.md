---
author: ['Marco Bonelli', 'Lucas Gabriel Schneider', 'Schneider', 'Jonathan Dahan']
date: 1612112718
title: "boot, TLDR Pages"
description: "boot, Build tooling for the Clojure programming language."
categories: "common"
---
> More information: <https://github.com/boot-clj/boot>.

- Start a REPL session either with the project or standalone:

```bash
boot repl
```

- Build a single `uberjar`:

```bash
boot jar
```

- Learn about a command:

```bash
boot cljs --help
```

- Generate scaffolding for a new project based on a template:

```bash
boot --dependencies boot/new new --template template_name --name project_name
```

- Build for development (if using the boot/new template):

```bash
boot dev
```

- Build for production (if using the boot/new template):

```bash
boot prod
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | multiple pages: format technical tokens (#5119) Co-authored-by: bl-ue <54780737+bl-ue@users.noreply.github.com> Co-authored-by: [...] | 2021-01-31T18:05:18 | [a5fe31bc47ae](https://github.com/tldr-pages/tldr/commit/a5fe31bc47aece3efa5e66b52b3cf384f27d5d72)
[Marco Bonelli](mailto:marco@mebeim.net) | Refactor: reword English pages' links' descriptions. | 2019-06-03T14:19:41 | [66abb98ce935](https://github.com/tldr-pages/tldr/commit/66abb98ce935c0f4516bf30c4d6da72180d5a3ab)
[Schneider](mailto:lucas.schneider@sap.com) | boot.md add homepage | 2019-04-11T09:49:15 | [c6c2c25a94a9](https://github.com/tldr-pages/tldr/commit/c6c2c25a94a9ee81d02949d8bc4874fe7ce16551)
[Jonathan Dahan](mailto:hi@jonathan.is) | Incorporate review feedback | 2017-12-04T15:48:43 | [fbdab559bca1](https://github.com/tldr-pages/tldr/commit/fbdab559bca150f0bca513acea0b7ef3386bfd5d)
[Jonathan Dahan](mailto:hi@jonathan.is) | boot: add page | 2017-12-02T12:05:04 | [a0d4ead488c6](https://github.com/tldr-pages/tldr/commit/a0d4ead488c60b2cea0af964b35804003de78fda)

