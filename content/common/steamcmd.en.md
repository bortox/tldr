---
author: ['Seth']
date: 1620653881
title: "steamcmd"
description: "steamcmd, A command-line version of the Steam client."
categories: "common"
---
> More information: <https://manned.org/steamcmd>.

- Install or update an application anonymously:

```bash
steamcmd +login anonymous +app_update appid +quit
```

- Install or update an application using the specified credentials:

```bash
steamcmd +login username +app_update appid +quit
```

- Install an application for a specific platform:

```bash
steamcmd +@sSteamCmdForcePlatformType windows +login anonymous +app_update appid validate +quit
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Seth](mailto:seth@falco.fun) | steamcmd: add page (#5922) | 2021-05-10T15:38:01 | [6e8b09845f8f](https://github.com/tldr-pages/tldr/commit/6e8b09845f8f6da7a91d7b0552d3012f108bd19e)

