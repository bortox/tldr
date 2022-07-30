---
author: ['NoPreserveRoot', 'Reinhart Previano Koentjoro']
date: 1638876003
title: "Get-FileHash"
description: "Get-FileHash, Calculate a hash for a file."
categories: "windows"
---
> This command can only be used through PowerShell.

> More information: <https://docs.microsoft.com/powershell/module/microsoft.powershell.utility/get-filehash>.

- Calculate a hash for a specified file using the SHA256 algorithm:

```bash
Get-FileHash path/to/file
```

- Calculate a hash for a specified file using a specified algorithm:

```bash
Get-FileHash path/to/file -Algorithm SHA1|SHA384|SHA256|SHA512|MD5
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Reinhart Previano Koentjoro](mailto:reinhart_previano@yahoo.com) | windows/get-*: add PowerShell-only notice (#7402) | 2021-12-07T12:20:03 | [19302554fb84](https://github.com/tldr-pages/tldr/commit/19302554fb842e9b0a6beb10c85eb5c5206678e9)
[NoPreserveRoot](mailto:NoPreserveRoot@pm.me) | get-filehash: add page (#7127) | 2021-10-23T07:14:35 | [e9b5ce396130](https://github.com/tldr-pages/tldr/commit/e9b5ce396130683c321adcc04e5feb7904201b6f)

