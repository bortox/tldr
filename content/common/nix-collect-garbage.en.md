---
author: ['pxgamer', 'Severin Fürbringer']
date: 1559676580
title: "nix-collect-garbage"
description: "nix-collect-garbage, Delete unused and unreachable nix store paths."
categories: "common"
---
> Generations can be listed using `nix-env --list-generations`.

> More information: <https://nixos.org/releases/nix/latest/manual/#sec-nix-collect-garbage>.

- Delete all store paths unused by current generations of each profile:

```bash
sudo nix-collect-garbage --delete-old
```

- Simulate the deletion of old store paths:

```bash
sudo nix-collect-garbage --delete-old --dry-run
```

- Delete all store paths older than 30 days:

```bash
sudo nix-collect-garbage --delete-older-than 30d
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[pxgamer](mailto:owzie123@gmail.com) | nix-collect-garbage: add link to homepage | 2019-06-04T21:29:40 | [3184a629ad0e](https://github.com/tldr-pages/tldr/commit/3184a629ad0ef2dd776bb5dc9e5aad3facb40d80)
[Severin Fürbringer](mailto:severin@protonmail.ch) | nix-collect-garbage: add page (#2090) | 2018-05-06T11:38:47 | [0cfcd52193c7](https://github.com/tldr-pages/tldr/commit/0cfcd52193c7d0f8d563ae7a3cd3316c7514264a)

