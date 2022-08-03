---
author: ['Emily Grace Seville', 'Lucas Gabriel Schneider', 'Christos Avlakiotis']
date: 1659498923
title: "wine"
description: "wine, Run Windows executables on Unix-based systems."
categories: "linux"
---
> More information: <https://wiki.winehq.org/>.

- Run a specific program inside the `wine` environment:

```bash
wine command
```

- Run a specific program in background:

```bash
wine start command
```

- Install/uninstall an MSI package:

```bash
wine msiexec /i|x path/to/package.msi
```

- Run `File Explorer`, `Notepad`, or `WordPad`:

```bash
wine explorer|notepad|write
```

- Run `Registry Editor`, `Control Panel`, or `Task Manager`:

```bash
wine regedit|control|taskmgr
```

- Run the configuration tool:

```bash
wine winecfg
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Emily Grace Seville](mailto:emilyseville7cf@gmail.com) | wine: refresh page (#8019) * Refresh page: - add new examples of running usual windows programs - make examples more general * Better [...] | 2022-08-03T05:55:23 | [c31eeb4cd523](https://github.com/tldr-pages/tldr/commit/c31eeb4cd523d2a5278b7135a74cc4272726a517)
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | multiple pages: format technical tokens (#5119) Co-authored-by: bl-ue <54780737+bl-ue@users.noreply.github.com> Co-authored-by: [...] | 2021-01-31T18:05:18 | [a5fe31bc47ae](https://github.com/tldr-pages/tldr/commit/a5fe31bc47aece3efa5e66b52b3cf384f27d5d72)
[Christos Avlakiotis](mailto:36479684+icsd12015@users.noreply.github.com) | wine: add page (#3453) Co-authored-by: Lucas Gabriel Schneider <casdpa@gmail.com> Co-authored-by: Agniva De Sarker <agnivade@yahoo.co.in> | 2019-12-25T14:15:17 | [8da0cdcb2607](https://github.com/tldr-pages/tldr/commit/8da0cdcb26076bf88aaf8406762cff0e9d7817fb)

