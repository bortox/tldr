---
author: ['Emily Grace Seville']
date: 1659570090
title: "powershell"
description: "powershell, Command-line shell and scripting language designed especially for system administration."
categories: "common"
---
> See also: `pwsh`.

> More information: <https://docs.microsoft.com/windows-server/administration/windows-commands/powershell>.

- Start an interactive shell session:

```bash
powershell
```

- Start an interactive shell session without loading startup configs:

```bash
powershell -NoProfile
```

- Execute specific commands:

```bash
powershell -Command "echo 'powershell is executed'"
```

- Execute a specific script:

```bash
powershell -File path/to/script.ps1
```

- Start a session with a specific version of PowerShell:

```bash
powershell -Version version
```

- Prevent a shell from exit after running startup commands:

```bash
powershell -NoExit
```

- Describe the format of data sent to PowerShell:

```bash
powershell -InputFormat Text|XML
```

- Determine how an output from PowerShell is formatted:

```bash
powershell -OutputFormat Text|XML
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Emily Grace Seville](mailto:emilyseville7cf@gmail.com) | powershell: refresh page (#7984) | 2022-08-04T01:41:30 | [289f1ad37897](https://github.com/tldr-pages/tldr/commit/289f1ad378972e97bd7250402ea628a4eb8fc008)

