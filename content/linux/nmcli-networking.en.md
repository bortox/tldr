---
author: ['marchersimon']
date: 1659183837
title: "nmcli networking"
description: "nmcli networking, Manage the networking status of NetworkManager."
categories: "linux"
---
> This subcommand can also be called with `nmcli n`.

> More information: <https://networkmanager.dev/docs/api/latest/nmcli.html>.

- Show the networking status of NetworkManager:

```bash
nmcli networking
```

- Enable or disable networking and all interfaces managed by NetworkManager:

```bash
nmcli networking on|off
```

- Show the last known connectivity state:

```bash
nmcli networking connectivity
```

- Show the current connectivity state:

```bash
nmcli networking connectivity check
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | nmcli-general, nmcli-networking: add page (#8264) * nmcli-general: add page * nmcli-networking: add page | 2022-07-30T14:23:57 | [236c68f8a851](https://github.com/tldr-pages/tldr/commit/236c68f8a8518255b7ca43f17ebe6390430cf853)

