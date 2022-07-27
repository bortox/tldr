---
author: ['Marco Bonelli', 'Aaron Janse']
date: 1559564381
title: "nixos-rebuild, TLDR Pages"
description: "nixos-rebuild, Reconfigure a NixOS machine."
categories: "linux"
---
> More information: <https://nixos.org/nixos/manual/#sec-changing-config>.

- Build and switch to the new configuration, making it the boot default:

```bash
sudo nixos-rebuild switch
```

- Build and switch to the new configuration, making it the boot default and naming the boot entry:

```bash
sudo nixos-rebuild switch -p name
```

- Build and switch to the new configuration, making it the boot default and installing updates:

```bash
sudo nixos-rebuild switch --upgrade
```

- Rollback changes to the configuration, switching to the previous generation:

```bash
sudo nixos-rebuild switch --rollback
```

- Build the new configuration and make it the boot default without switching to it:

```bash
sudo nixos-rebuild boot
```

- Build and activate the new configuration, but don't make a boot entry (for testing purposes):

```bash
sudo nixos-rebuild test
```

- Build the configuration and open it in a virtual machine:

```bash
sudo nixos-rebuild build-vm
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Marco Bonelli](mailto:marco@mebeim.net) | Refactor: reword English pages' links' descriptions. | 2019-06-03T14:19:41 | [66abb98ce935](https://github.com/tldr-pages/tldr/commit/66abb98ce935c0f4516bf30c4d6da72180d5a3ab)
[Aaron Janse](mailto:aaron@ajanse.me) | nixos-rebuild: add page (#2809) | 2019-03-02T12:36:13 | [8edc5b4fdbc6](https://github.com/tldr-pages/tldr/commit/8edc5b4fdbc67de1042e57ca55174f48c2394bc6)

