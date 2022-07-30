---
author: ['Lucas Gabriel Schneider', 'Christos Avlakiotis']
date: 1612112718
title: "wine"
description: "wine, Run Windows programs on Unix."
categories: "linux"
---
> More information: <https://wiki.winehq.org/>.

- Run `ipconfig.exe` program:

```bash
wine ipconfig /all
```

- Run `cmd.exe` in background:

```bash
wine start cmd
```

- Run Windows-like Package Manager:

```bash
wine uninstaller
```

- Install MSI packages:

```bash
wine msiexec /i package
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | multiple pages: format technical tokens (#5119) Co-authored-by: bl-ue <54780737+bl-ue@users.noreply.github.com> Co-authored-by: [...] | 2021-01-31T18:05:18 | [a5fe31bc47ae](https://github.com/tldr-pages/tldr/commit/a5fe31bc47aece3efa5e66b52b3cf384f27d5d72)
[Christos Avlakiotis](mailto:36479684+icsd12015@users.noreply.github.com) | wine: add page (#3453) Co-authored-by: Lucas Gabriel Schneider <casdpa@gmail.com> Co-authored-by: Agniva De Sarker <agnivade@yahoo.co.in> | 2019-12-25T14:15:17 | [8da0cdcb2607](https://github.com/tldr-pages/tldr/commit/8da0cdcb26076bf88aaf8406762cff0e9d7817fb)

