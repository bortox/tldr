---
author: ['Sebastian Staudt', 'skitau']
date: 1633783663
title: "gpupdate"
description: "gpupdate, A tool to check and apply Windows Group Policy settings."
categories: "windows"
---
> More information: <https://docs.microsoft.com/windows-server/administration/windows-commands/gpupdate>.

- Check and apply updated Group Policy settings:

```bash
gpupdate
```

- Specify the target Group Policy settings to check for update:

```bash
gpupdate /target:computer|user
```

- Force all Group Policy settings to be reapplied:

```bash
gpupdate /force
```

- Display detailed usage information:

```bash
gpupdate /?
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Sebastian Staudt](mailto:koraktor@gmail.com) | gpupdate: fix target syntax (#6727) | 2021-10-09T14:47:43 | [0a2fed181338](https://github.com/tldr-pages/tldr/commit/0a2fed1813388f459b828f3f5d67e07eec3b0caf)
[skitau](mailto:robert@blackstock.id.au) | gpupdate: add page (#4772) | 2020-10-28T19:50:05 | [8d1bfcbb031f](https://github.com/tldr-pages/tldr/commit/8d1bfcbb031ffe8a1d14d281399b36ae5703b2fb)

