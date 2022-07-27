---
author: ['CleanMachine1', 'godalming123']
date: 1656627412
title: "dm-tool, TLDR Pages"
description: "dm-tool, A tool to communicate with the display manager."
categories: "linux"
---
> More information: <https://manned.org/dm-tool>.

- Show the greeter while keeping current desktop session open and waiting to be restored upon authentication by logged in user:

```bash
dm-tool switch-to-greeter
```

- Lock the current session:

```bash
dm-tool lock
```

- Switch to a specific user, showing an authentication prompt if required:

```bash
dm-tool switch-to-user username session
```

- Add a dynamic seat from within a running LightDM session:

```bash
dm-tool add-seat xlocal name=value
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[CleanMachine1](mailto:78213164+CleanMachine1@users.noreply.github.com) | *: fix spelling mistakes | 2022-07-01T00:16:52 | [fe3fa89cb5dc](https://github.com/tldr-pages/tldr/commit/fe3fa89cb5dcd33fed00c70a5d789006a425068e)
[godalming123](mailto:r2hk9ahnf@relay.firefox.com) | dm-tool: add page (#7710) | 2022-02-02T12:05:01 | [daf0125df64e](https://github.com/tldr-pages/tldr/commit/daf0125df64e58d509873d08dfbb550f63f6dbfb)

