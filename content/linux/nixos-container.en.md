---
author: ['Ryan Lahfa']
date: 1635390543
title: "nixos-container, TLDR Pages"
description: "nixos-container, Starts NixOS containers using Linux containers."
categories: "linux"
---
> More information: <https://nixos.org/manual/nixos/stable/#ch-containers>.

- List running containers:

```bash
sudo nixos-container list
```

- Create a NixOS container with a specific configuration file:

```bash
sudo nixos-container create container_name --config-file nix_config_file_path
```

- Start, stop, terminate, or destroy a specific container:

```bash
sudo nixos-container start|stop|terminate|destroy|status container_name
```

- Run a command in a running container:

```bash
sudo nixos-container run container_name -- command command_arguments
```

- Update a container configuration:

```bash
sudo $EDITOR /var/lib/container/container_name/etc/nixos/configuration.nix && sudo nixos-container update container_name
```

- Enter an interactive shell session on an already-running container:

```bash
sudo nixos-container root-login container_name
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Ryan Lahfa](mailto:masterancpp@gmail.com) | nixos-container: add page (#7163) | 2021-10-28T05:09:03 | [e13b2991341c](https://github.com/tldr-pages/tldr/commit/e13b2991341c54efa1b0f7c68e107aae1e47e553)

