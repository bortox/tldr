---
author: ['Sebastian Staudt']
date: 1633376786
title: "setx"
description: "setx, Sets persistent environment variables."
categories: "windows"
---
> More information: <https://docs.microsoft.com/windows-server/administration/windows-commands/setx>.

- Set an environment variable for the current user:

```bash
setx variable value
```

- Set an environment variable for the current machine:

```bash
setx variable value /M
```

- Set an environment variable for a user on a remote machine:

```bash
setx /s hostname /u username /p password variable value
```

- Set an environment variable from a registry key value:

```bash
setx variable /k registry\key\path
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Sebastian Staudt](mailto:koraktor@gmail.com) | setx: add page (#6734) | 2021-10-04T21:46:26 | [88d446edc9e6](https://github.com/tldr-pages/tldr/commit/88d446edc9e6ea3e58c7a0f2f51e77457c844b85)

