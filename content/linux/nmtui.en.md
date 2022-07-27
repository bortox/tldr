---
author: ['Saksham Mittal', 'haloboy777']
date: 1635779360
title: "nmtui, TLDR Pages"
description: "nmtui, Text user interface for controlling NetworkManager."
categories: "linux"
---
> Use arrow keys to navigate, enter to select an option.

> More information: <https://networkmanager.dev/docs/api/latest/nmtui.html>.

- Open the user interface:

```bash
nmtui
```

- Show a list of available connections, with the option to activate or deactivate them:

```bash
nmtui connect
```

- Connect to a given network:

```bash
nmtui connect name|uuid|device|SSID
```

- Edit/Add/Delete a given network:

```bash
nmtui edit name|id
```

- Set the system hostname:

```bash
nmtui hostname
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Saksham Mittal](mailto:gotlougit@users.noreply.github.com) | nmtui: add more information link (#7348) | 2021-11-01T16:09:20 | [3ae5dd0e3970](https://github.com/tldr-pages/tldr/commit/3ae5dd0e39700cd9d4eef7110a3ccbe7b544c618)
[haloboy777](mailto:haloboy777@users.noreply.github.com) | nmtui.md: add page (#1613) | 2018-01-19T20:04:49 | [d5146c9f47e4](https://github.com/tldr-pages/tldr/commit/d5146c9f47e420724a86402770e68f899a46a16f)

