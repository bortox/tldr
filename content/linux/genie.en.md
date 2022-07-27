---
author: ['Alistair Young']
date: 1565197225
title: "genie, TLDR Pages"
description: "genie, Set up and use a 'bottle' namespace to run systemd under WSL (Windows Subsystem for Linux)."
categories: "linux"
---
> To run these from Windows rather than an already-running distribution, precede them with `wsl`.

> More information: <https://github.com/arkane-systems/genie>.

- Initialize the bottle (run once, at start):

```bash
genie -i
```

- Run a login shell inside the bottle:

```bash
genie -s
```

- Run a specified command inside the bottle:

```bash
genie -c command
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Alistair Young](mailto:avatar@arkane-systems.net) | genie: add page (#3224) | 2019-08-07T19:00:25 | [764d21abadf1](https://github.com/tldr-pages/tldr/commit/764d21abadf1d60a774224c813c036bb032ef114)

