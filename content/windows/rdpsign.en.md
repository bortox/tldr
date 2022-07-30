---
author: ['Waldir Pimenta', 'Owen Voke', 'Lucas Gabriel Schneider']
date: 1612112718
title: "rdpsign"
description: "rdpsign, A tool for signing Remote Desktop Protocol (RDP) files."
categories: "windows"
---
> More information: <https://docs.microsoft.com/windows-server/administration/windows-commands/rdpsign>.

- Sign an RDP file:

```bash
rdpsign path/to/file.rdp
```

- Sign an RDP file using a specific sha256 hash:

```bash
rdpsign path/to/file.rdp /sha265 hash
```

- Enable quiet output:

```bash
rdpsign path/to/file.rdp /q
```

- Display verbose warnings, messages and statuses:

```bash
rdpsign path/to/file.rdp /v
```

- Test the signing by displaying the output to stdout without updating the file:

```bash
rdpsign path/to/file.rdp /l
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | multiple pages: format technical tokens (#5119) Co-authored-by: bl-ue <54780737+bl-ue@users.noreply.github.com> Co-authored-by: [...] | 2021-01-31T18:05:18 | [a5fe31bc47ae](https://github.com/tldr-pages/tldr/commit/a5fe31bc47aece3efa5e66b52b3cf384f27d5d72)
[Owen Voke](mailto:development@voke.dev) | windows.*: remove locale from page urls | 2020-09-22T19:06:55 | [8f9a4b1f5cff](https://github.com/tldr-pages/tldr/commit/8f9a4b1f5cff138652665e9756a1a13466029fed)
[Lucas Gabriel Schneider](mailto:lucas.schneider@sap.com) | multiple pages: add homepages (#3250) | 2019-08-22T14:37:57 | [cd926556204e](https://github.com/tldr-pages/tldr/commit/cd926556204e9b8d34858b141886c675e8e0b83a)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | Harmonize formatting and capitalization of stdin/stdout/stderr | 2019-06-17T18:39:58 | [cf25745db1d8](https://github.com/tldr-pages/tldr/commit/cf25745db1d86744c762e15e6a2ba04ef9f9acc1)
[Owen Voke](mailto:owzie123@gmail.com) | rdpsign: add page (#2433) | 2018-10-14T14:05:42 | [8a275a3123aa](https://github.com/tldr-pages/tldr/commit/8a275a3123aa8b28bf60369811df9e5a8649a72c)

