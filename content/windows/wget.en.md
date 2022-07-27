---
author: ['Reinhart Previano Koentjoro']
date: 1657669284
title: "wget, TLDR Pages"
description: "wget, In PowerShell, this command may be an alias of `Invoke-WebRequest` when the original `wget` program (<https://www.gnu.org/software/wget>) is not properly installed."
categories: "windows"
---
- Check whether `wget` is properly installed by printing its version number. If this command evaluates into an error, PowerShell may have substituted this command with `Invoke-WebRequest`:

```bash
curl --version
```

- View documentation for the original `wget` command:

```bash
tldr wget -p common
```

- View documentation for PowerShell's `Invoke-WebRequest` command:

```bash
tldr invoke-webrequest
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Reinhart Previano Koentjoro](mailto:reinhart_previano@yahoo.com) | invoke-webrequest: add page (#8177) * windows/get-*: Add PowerShell-only notice * Update pages/windows/get-childitem.md Co-authored- [...] | 2022-07-13T01:41:24 | [dc3ec3556046](https://github.com/tldr-pages/tldr/commit/dc3ec3556046aa804d0224bb54dd27ab6001e449)

