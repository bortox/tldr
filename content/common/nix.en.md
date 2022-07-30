---
author: ['Mathis Chenuet', 'Aaron Janse', 'pxgamer']
date: 1650833292
title: "nix"
description: "nix, Utilities for the Nix language and store."
categories: "common"
---
> More information: <https://nixos.org>.

- Search for a package via its name or description:

```bash
nix search search_term
```

- Start a Nix shell with the specified packages available:

```bash
nix run nixpkgs.pkg1 nixpkgs.pkg2 nixpkgs.pkg3...
```

- Optimise Nix store disk usage by combining duplicate files:

```bash
nix store optimise
```

- Start an interactive environment for evaluating Nix expressions:

```bash
nix repl
```

- Upgrade Nix to the latest stable version:

```bash
nix upgrade-nix
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Mathis Chenuet](mailto:9201969+artemisart@users.noreply.github.com) | nix: fix deprecated optimise-store example (#8050) | 2022-04-24T22:48:12 | [ffb0d53765da](https://github.com/tldr-pages/tldr/commit/ffb0d53765da6b56edb23f27384b698a054d7be6)
[pxgamer](mailto:owzie123@gmail.com) | nix: add link to homepage | 2019-06-04T21:29:40 | [97d61e6cd512](https://github.com/tldr-pages/tldr/commit/97d61e6cd512da4080ff592e1501742a04c27ede)
[Aaron Janse](mailto:aaron@ajanse.me) | nix: add page (#2808) | 2019-03-04T11:46:18 | [4f29c32f0015](https://github.com/tldr-pages/tldr/commit/4f29c32f00151b126844760ea4920fee73e40397)

