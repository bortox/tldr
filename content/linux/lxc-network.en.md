---
author: ['Mat']
date: 1636232885
title: "lxc network, TLDR Pages"
description: "lxc network, Manage networks for LXD containers."
categories: "linux"
---
> More information: <https://linuxcontainers.org/lxd/docs/master/networks>.

- List all available networks:

```bash
lxc network list
```

- Show the configuration of a specific network:

```bash
lxc network show network_name
```

- Add a running instance to a specific network:

```bash
lxc network attach network_name container_name
```

- Create a new managed network:

```bash
lxc network create network_name
```

- Set a bridge interface of a specific network:

```bash
lxc network set network_name bridge.external_interfaces eth0
```

- Disable NAT for a specific network:

```bash
lxc network set network_name ipv4.nat false
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Mat](mailto:mtausig@users.noreply.github.com) | lxc-network, lxc-profile: add page (#7280) | 2021-11-06T22:08:05 | [a60f1f9fae55](https://github.com/tldr-pages/tldr/commit/a60f1f9fae552d2b7f69a9b9206ee37d79b8dbe5)

