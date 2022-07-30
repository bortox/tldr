---
author: ['marchersimon']
date: 1659183837
title: "nmcli general"
description: "nmcli general, Manage general settings of NetworkManager."
categories: "linux"
---
> This subcommand can also be called with `nmcli g`.

> More information: <https://networkmanager.dev/docs/api/latest/nmcli.html>.

- Show the general status of NetworkManager:

```bash
nmcli general
```

- Show the hostname of the current device:

```bash
nmcli general hostname
```

- Change the hostname of the current device:

```bash
sudo nmcli general hostname new_hostname
```

- Show the permissions of NetworkManager:

```bash
nmcli general permissions
```

- Show the current logging level and domains:

```bash
nmcli general logging
```

- Set the logging level and/or domains (see `man NetworkManager.conf` for all available domains):

```bash
nmcli general logging level INFO|OFF|ERR|WARN|DEBUG|TRACE domain domain_1,domain_2,...
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | nmcli-general, nmcli-networking: add page (#8264) * nmcli-general: add page * nmcli-networking: add page | 2022-07-30T14:23:57 | [236c68f8a851](https://github.com/tldr-pages/tldr/commit/236c68f8a8518255b7ca43f17ebe6390430cf853)

