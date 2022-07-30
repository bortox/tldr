---
author: ['Mat']
date: 1636232885
title: "lxc profile"
description: "lxc profile, Manage profiles for LXD containers."
categories: "linux"
---
> More information: <https://linuxcontainers.org/lxd/docs/master/profiles>.

- List all available profiles:

```bash
lxc profile list
```

- Show the configuration of a specific profile:

```bash
lxc profile show profile_name
```

- Edit a specific profile in the default editor:

```bash
lxc profile edit profile_name
```

- Edit a specific profile importing the configuration values from a file:

```bash
lxc profile edit profile_name < config.yaml
```

- Launch a new container with specific profiles:

```bash
lxc launch container_image container_name --profile profile1 --profile profile2
```

- Change the profiles of a running container:

```bash
lxc profile assign container_name profile1,profile2
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Mat](mailto:mtausig@users.noreply.github.com) | lxc-network, lxc-profile: add page (#7280) | 2021-11-06T22:08:05 | [a60f1f9fae55](https://github.com/tldr-pages/tldr/commit/a60f1f9fae552d2b7f69a9b9206ee37d79b8dbe5)

