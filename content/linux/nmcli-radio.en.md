---
author: ['git-em']
date: 1646866093
title: "nmcli radio, TLDR Pages"
description: "nmcli radio, Show radio switches status or enable and disable switches."
categories: "linux"
---
> See also: `nmcli agent`.

> More information: <https://networkmanager.dev/docs/api/latest/nmcli.html>.

- Show status of Wi-Fi in NetworkManager:

```bash
nmcli radio wifi
```

- Turn Wi-Fi on or off in NetworkManager:

```bash
nmcli radio wifi on|off
```

- Show status of WWAN in NetworkManager:

```bash
nmcli radio wwan
```

- Turn WWAN on or off in NetworkManager:

```bash
nmcli radio wwan on|off
```

- Show status of both switches in NetworkManager:

```bash
nmcli radio all
```

- Turn both switches on or off in NetworkManager:

```bash
nmcli radio all on|off
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[git-em](mailto:56173216+git-em@users.noreply.github.com) | nmcli-agent, nmcli-radio: add page (#7863) | 2022-03-09T23:48:13 | [cbfe325cb1ec](https://github.com/tldr-pages/tldr/commit/cbfe325cb1ec1221e5d16fcf9c9da5cc27a3d408)

