---
author: ['Reinhart Previano Koentjoro', 'Willian Lopes']
date: 1638876003
title: "Get-Content, TLDR Pages"
description: "Get-Content, Get the content of the item at the specified location."
categories: "windows"
---
> This command can only be used through PowerShell.

> More information: <https://docs.microsoft.com/powershell/module/microsoft.powershell.management/get-content>.

- Display the content of a file:

```bash
Get-Content -Path path/to/file
```

- Display the first few lines of a file:

```bash
Get-Content -Path path/to/file -TotalCount count
```

- Display the content of the file and keep reading from it until `Ctrl + C` is pressed:

```bash
Get-Content -Path path/to/file -Wait
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Reinhart Previano Koentjoro](mailto:reinhart_previano@yahoo.com) | windows/get-*: add PowerShell-only notice (#7402) | 2021-12-07T12:20:03 | [19302554fb84](https://github.com/tldr-pages/tldr/commit/19302554fb842e9b0a6beb10c85eb5c5206678e9)
[Willian Lopes](mailto:williangldzn@gmail.com) | get-content: add page (#4687) | 2020-11-29T07:02:43 | [90baf7ecf499](https://github.com/tldr-pages/tldr/commit/90baf7ecf4991c311ea9891b8dda1be47dd505a2)

