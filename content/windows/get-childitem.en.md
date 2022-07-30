---
author: ['NoPreserveRoot', 'Reinhart Previano Koentjoro']
date: 1638876003
title: "Get-ChildItem"
description: "Get-ChildItem, List items in a directory."
categories: "windows"
---
> This command can only be used through PowerShell.

> More information: <https://docs.microsoft.com/powershell/module/microsoft.powershell.management/get-childitem>.

- List all non-hidden items in the current directory:

```bash
Get-ChildItem
```

- List only directories in the current directory:

```bash
Get-ChildItem -Directory
```

- List only files in the current directory:

```bash
Get-ChildItem -File
```

- List items in the current directory, including hidden items:

```bash
Get-ChildItem -Hidden
```

- List items in a directory other than the current one:

```bash
Get-ChildItem -Path path/to/directory
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Reinhart Previano Koentjoro](mailto:reinhart_previano@yahoo.com) | windows/get-*: add PowerShell-only notice (#7402) | 2021-12-07T12:20:03 | [19302554fb84](https://github.com/tldr-pages/tldr/commit/19302554fb842e9b0a6beb10c85eb5c5206678e9)
[NoPreserveRoot](mailto:NoPreserveRoot@pm.me) | get-childitem: add page (#6818) | 2021-10-12T08:18:02 | [e599b2e73e0e](https://github.com/tldr-pages/tldr/commit/e599b2e73e0e6f1b14b3a40313e1bf54dddf2d85)

