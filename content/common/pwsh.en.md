---
author: ['Seth Falco']
date: 1627528010
title: "pwsh, TLDR Pages"
description: "pwsh, PowerShell Core is a cross-platform automation and configuration tool/framework."
categories: "common"
---
> More information: <https://docs.microsoft.com/powershell/>.

- Start an instance of PowerShell:

```bash
pwsh
```

- Execute a script and then exit:

```bash
pwsh -File path/to/file.ps1
```

- Set the execution policy for the current session:

```bash
pwsh -ExecutionPolicy AllSigned|Bypass|Default|RemoteSigned|Restricted|Undefined|Unrestricted
```

- Execute a command and then exit:

```bash
pwsh -Command command
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Seth Falco](mailto:seth@falco.fun) | pwsh: add page (#6249) | 2021-07-29T05:06:50 | [7d72acec88f5](https://github.com/tldr-pages/tldr/commit/7d72acec88f5571bf02e1c071f3678b23c7da514)

