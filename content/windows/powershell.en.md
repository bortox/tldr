---
author: ['Adhiraj']
date: 1602712869
title: "powershell"
description: "powershell, Command-line shell and scripting language designed especially for system administration."
categories: "windows"
---
> More information: <https://docs.microsoft.com/windows-server/administration/windows-commands/powershell>.

- Start a Windows PowerShell session in a Command Prompt window:

```bash
powershell
```

- Load a specific PowerShell console file:

```bash
powershell -PSConsoleFile path/to/file
```

- Start a session with a specified version of PowerShell:

```bash
powershell -Version version
```

- Prevent the shell from exit after running startup commands:

```bash
powershell -NoExit
```

- Describe the format of data sent to PowerShell:

```bash
powershell -InputFormat Text|XML
```

- Determine how output from PowerShell is formatted:

```bash
powershell -OutputFormat Text|XML
```

- Display help:

```bash
powershell -Help
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Adhiraj](mailto:adhirajd007@gmail.com) | powershell: add page (#4634) | 2020-10-15T00:01:09 | [dbd00033b520](https://github.com/tldr-pages/tldr/commit/dbd00033b520d6e2b2398b3666e46a96306515b5)

