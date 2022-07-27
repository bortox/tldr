---
author: ['Morgan Erlich']
date: 1609539158
title: "nix-shell, TLDR Pages"
description: "nix-shell, Start an interactive shell based on a Nix expression."
categories: "common"
---
> More information: <https://nixos.org/manual/nix/stable/#sec-nix-shell>.

- Start with nix expression in `shell.nix` or `default.nix` in the current directory:

```bash
nix-shell
```

- Run shell command in non-interactive shell and exit:

```bash
nix-shell --run "command command_arguments"
```

- Start with expression in `default.nix` in the current directory:

```bash
nix-shell default.nix
```

- Start with packages loaded from nixpkgs:

```bash
nix-shell --packages package_name_1 package_name_2
```

- Start with packages loaded from specific nixpkgs revision:

```bash
nix-shell --packages package_names -I nixpkgs=https://github.com/NixOS/nixpkgs/archive/nixpkgs_revision.tar.gz
```

- Evaluate rest of file in specific interpreter, for use in `#!-scripts` (see <https://nixos.org/manual/nix/stable/#use-as-a-interpreter>):

```bash
nix-shell -i interpreter --packages package_names
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Morgan Erlich](mailto:nagromlobo@gmail.com) | nix-shell, nix-env: add page and fix manual link (#5060) | 2021-01-01T23:12:38 | [ffa6317a54f3](https://github.com/tldr-pages/tldr/commit/ffa6317a54f3f83067f1c07fbe0205c2c6affa37)

