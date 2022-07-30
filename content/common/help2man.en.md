---
author: ['Waldir Pimenta', 'pxgamer', 'Lucas Gabriel Schneider']
date: 1612112718
title: "help2man"
description: "help2man, Produce simple man pages from an executable's `--help` and `--version` output."
categories: "common"
---
> More information: <https://www.gnu.org/software/help2man>.

- Generate a man page for an executable:

```bash
help2man executable
```

- Specify the "name" paragraph in the man page:

```bash
help2man executable --name name
```

- Specify the section for the man page (defaults to 1):

```bash
help2man executable --section section
```

- Output to a file instead of stdout:

```bash
help2man executable --output path/to/file
```

- Display detailed help:

```bash
help2man --help
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | multiple pages: format technical tokens (#5119) Co-authored-by: bl-ue <54780737+bl-ue@users.noreply.github.com> Co-authored-by: [...] | 2021-01-31T18:05:18 | [a5fe31bc47ae](https://github.com/tldr-pages/tldr/commit/a5fe31bc47aece3efa5e66b52b3cf384f27d5d72)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | Harmonize formatting and capitalization of stdin/stdout/stderr | 2019-06-17T18:39:58 | [cf25745db1d8](https://github.com/tldr-pages/tldr/commit/cf25745db1d86744c762e15e6a2ba04ef9f9acc1)
[pxgamer](mailto:owzie123@gmail.com) | help2man: add link to homepage | 2019-06-07T23:58:59 | [b32ee8ed2b3e](https://github.com/tldr-pages/tldr/commit/b32ee8ed2b3e228178adc3fba99df6ea290f47a2)
[pxgamer](mailto:owzie123@gmail.com) | help2man: update to remove unnecessary examples | 2018-05-11T18:19:45 | [36775b855883](https://github.com/tldr-pages/tldr/commit/36775b85588304e48e6f01a9f9b733cfd66f7b04)
[pxgamer](mailto:owzie123@gmail.com) | help2man: add page | 2018-05-11T18:19:45 | [ba4194d4a047](https://github.com/tldr-pages/tldr/commit/ba4194d4a04797b8776978122ccf3c5b5ccaa366)

