---
author: ['Reinhart Previano Koentjoro']
date: 1641546916
title: "Invoke-Item, TLDR Pages"
description: "Invoke-Item, Open files in their respective default programs."
categories: "windows"
---
> This command can only be used through PowerShell.

> More information: <https://docs.microsoft.com/powershell/module/microsoft.powershell.management/invoke-item>.

- Open a file in its default program:

```bash
Invoke-Item -Path path/to/file
```

- Open all files inside a directory:

```bash
Invoke-Item -Path path/to/directory/*
```

- Open all PNGs inside a directory:

```bash
Invoke-Item -Path path/to/directory/*.png
```

- Open all files inside a directory containing a specific keyword:

```bash
Invoke-Item -Path path/to/directory/* -Include *keyword*
```

- Open all files inside a directory except those containing a specific keyword:

```bash
Invoke-Item -Path path/to/directory/* -Exclude *keyword*
```

- Perform a dry run to determine which files will be opened inside a directory through `Invoke-Item`:

```bash
Invoke-Item -Path path/to/directory/* -WhatIf
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Reinhart Previano Koentjoro](mailto:reinhart_previano@yahoo.com) | invoke-item: add page (#7517) | 2022-01-07T10:15:16 | [fce802ddb041](https://github.com/tldr-pages/tldr/commit/fce802ddb0412cfeba3044291f418e0b744b2ef0)

