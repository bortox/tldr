---
author: ['NoPreserveRoot', 'Reinhart Previano Koentjoro']
date: 1638876003
title: "Get-History"
description: "Get-History, Display PowerShell command history."
categories: "windows"
---
> This command can only be used through PowerShell.

> More information: <https://docs.microsoft.com/powershell/module/microsoft.powershell.core/get-history>.

- Display the commands history list with ID:

```bash
Get-History
```

- Get PowerShell history item by ID:

```bash
Get-History -Id id
```

- Display the last N commands:

```bash
Get-History -Count count
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Reinhart Previano Koentjoro](mailto:reinhart_previano@yahoo.com) | windows/get-*: add PowerShell-only notice (#7402) | 2021-12-07T12:20:03 | [19302554fb84](https://github.com/tldr-pages/tldr/commit/19302554fb842e9b0a6beb10c85eb5c5206678e9)
[NoPreserveRoot](mailto:NoPreserveRoot@pm.me) | get-history: add page (#7126) | 2021-10-24T04:25:21 | [9b4ded37e813](https://github.com/tldr-pages/tldr/commit/9b4ded37e8137a635cafa85b5e6d38918911f407)

