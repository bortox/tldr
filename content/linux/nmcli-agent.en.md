---
author: ['git-em']
date: 1646866093
title: "nmcli agent, TLDR Pages"
description: "nmcli agent, Run nmcli as a NetworkManager secret agent or polkit agent."
categories: "linux"
---
> See also: `nmcli radio`.

> More information: <https://networkmanager.dev/docs/api/latest/nmcli.html>.

- Register nmcli as a secret agent and listen for secret requests:

```bash
nmcli agent secret
```

- Register nmcli as a polkit agent and listen for authorization requests:

```bash
nmcli agent polkit
```

- Register nmcli as a secret agent and a polkit agent:

```bash
nmcli agent all
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[git-em](mailto:56173216+git-em@users.noreply.github.com) | nmcli-agent, nmcli-radio: add page (#7863) | 2022-03-09T23:48:13 | [cbfe325cb1ec](https://github.com/tldr-pages/tldr/commit/cbfe325cb1ec1221e5d16fcf9c9da5cc27a3d408)

