---
author: ['Waldir Pimenta', 'Lucas Gabriel Schneider', 'pxgamer', 'Owen Voke']
date: 1612112718
title: "more, TLDR Pages"
description: "more, Display paginated output from stdin or a file."
categories: "windows"
---
> More information: <https://docs.microsoft.com/windows-server/administration/windows-commands/more>.

- Display paginated output from stdin:

```bash
echo test | more
```

- Display paginated output from one or more files:

```bash
more path/to/file
```

- Convert tabs to the specified number of spaces:

```bash
more path/to/file /tspaces
```

- Clear the screen before displaying the page:

```bash
more path/to/file /c
```

- Display the output starting at line 5:

```bash
more path/to/file +5
```

- Enable extended interactive mode (see help for usage):

```bash
more path/to/file /e
```

- Display full usage information:

```bash
more /?
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | multiple pages: format technical tokens (#5119) Co-authored-by: bl-ue <54780737+bl-ue@users.noreply.github.com> Co-authored-by: [...] | 2021-01-31T18:05:18 | [a5fe31bc47ae](https://github.com/tldr-pages/tldr/commit/a5fe31bc47aece3efa5e66b52b3cf384f27d5d72)
[Owen Voke](mailto:development@voke.dev) | windows.*: remove locale from page urls | 2020-09-22T19:06:55 | [8f9a4b1f5cff](https://github.com/tldr-pages/tldr/commit/8f9a4b1f5cff138652665e9756a1a13466029fed)
[Lucas Gabriel Schneider](mailto:lucas.schneider@sap.com) | multiple pages: add homepages (#3250) | 2019-08-22T14:37:57 | [cd926556204e](https://github.com/tldr-pages/tldr/commit/cd926556204e9b8d34858b141886c675e8e0b83a)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | Harmonize formatting and capitalization of stdin/stdout/stderr | 2019-06-17T18:39:58 | [cf25745db1d8](https://github.com/tldr-pages/tldr/commit/cf25745db1d86744c762e15e6a2ba04ef9f9acc1)
[pxgamer](mailto:owzie123@gmail.com) | more: add missing backtick | 2018-10-11T11:38:21 | [82efd2c5731c](https://github.com/tldr-pages/tldr/commit/82efd2c5731c65abaaaab5fbfbd901bef3d41b28)
[pxgamer](mailto:owzie123@gmail.com) | more: add page | 2018-10-11T11:38:21 | [a838644666ed](https://github.com/tldr-pages/tldr/commit/a838644666ed470b2988fd02e116c90cde421fcd)

