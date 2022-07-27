---
author: ['Ryan Lahfa']
date: 1635806826
title: "nixos-option, TLDR Pages"
description: "nixos-option, Inspect a NixOS configuration."
categories: "linux"
---
> More information: <https://nixos.org/manual/nixos/stable/index.html#sec-modularity>.

- List all subkeys of a given option key:

```bash
nixos-option option_key
```

- List current boot kernel modules:

```bash
nixos-option boot.kernelModules
```

- List authorized keys for a specific user:

```bash
nixos-option users.users.username.openssh.authorizedKeys.keyFiles|keys
```

- List all remote builders:

```bash
nixos-option nix.buildMachines
```

- List all subkeys of a given key on another NixOS configuration:

```bash
NIXOS_CONFIG=path_to_configuration.nix nixos-option option_key
```

- Show recursively all values of a user:

```bash
nixos-option -r users.users.user
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Ryan Lahfa](mailto:masterancpp@gmail.com) | nixos-option: add page (#7166) | 2021-11-01T23:47:06 | [4cda2b182cd3](https://github.com/tldr-pages/tldr/commit/4cda2b182cd314bf0234066bc54411451705551c)

