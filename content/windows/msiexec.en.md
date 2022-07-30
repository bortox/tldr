---
author: ['Reinhart Previano Koentjoro']
date: 1639390877
title: "msiexec"
description: "msiexec, Install, update, repair, or uninstall Windows programs using MSI and MSP package files."
categories: "windows"
---
> More information: <https://docs.microsoft.com/windows-server/administration/windows-commands/msiexec>.

- Install a program from its MSI package:

```bash
msiexec /package path/to/file.msi
```

- Install a MSI package from a website:

```bash
msiexec /package https://example.com/installer.msi
```

- Install a MSP patch file:

```bash
msiexec /update path/to/file.msp
```

- Uninstall a program or patch using their respective MSI or MSP file:

```bash
msiexec /uninstall path/to/file
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Reinhart Previano Koentjoro](mailto:reinhart_previano@yahoo.com) | msiexec: add page (#7513) | 2021-12-13T11:21:17 | [bb70cb419426](https://github.com/tldr-pages/tldr/commit/bb70cb4194261774be0cc4a3fbe117a46faf4c25)

