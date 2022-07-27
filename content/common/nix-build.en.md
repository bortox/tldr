---
author: ['Americo', 'bl-ue']
date: 1621541621
title: "nix-build, TLDR Pages"
description: "nix-build, Build a Nix expression."
categories: "common"
---
> More information: <https://nixos.org/releases/nix/latest/manual#sec-nix-build>.

- Build a Nix expression:

```bash
nix-build --attr expression_name
```

- Build a sandboxed Nix expression (on non-NixOS):

```bash
nix-build --attr expression_name --option sandbox true
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | *: fix typos reported by Hunspell (#5848) Co-authored-by: marchersimon <50295997+marchersimon@users.noreply.github.com> Co-authored- [...] | 2021-05-20T22:13:41 | [8ebd171d6f00](https://github.com/tldr-pages/tldr/commit/8ebd171d6f001698709fefc02b1fd5cc9f3a99c4)
[Americo](mailto:ame.zuz@gmail.com) | nix-build: add page | 2019-11-05T22:37:16 | [9a09ce625626](https://github.com/tldr-pages/tldr/commit/9a09ce625626372721ee3669f96407d7912ef1d4)

