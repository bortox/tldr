---
author: ['Owen Voke', 'Lucas Gabriel Schneider', 'Seth Falco']
date: 1629050349
title: "wapm"
description: "wapm, The WebAssembly package manager."
categories: "common"
---
> More information: <https://wapm.io/help/reference>.

- Interactively create a new `wapm.toml` file:

```bash
wapm init
```

- Download all the packages listed as dependencies in `wapm.toml`:

```bash
wapm install
```

- Download a specific version of a package and add it to the list of dependencies in wapm.toml:

```bash
wapm install package_name@version
```

- Download a package and install it globally:

```bash
wapm install --global package_name
```

- Uninstall a package and remove it from the list of dependencies in `wapm.toml`:

```bash
wapm uninstall package_name
```

- Print a tree of locally installed dependencies:

```bash
wapm list
```

- List top-level globally installed packages:

```bash
wapm list --global
```

- Execute a package command using the Wasmer runtime:

```bash
wapm run command_name arguments
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Seth Falco](mailto:seth@falco.fun) | *: fix errors reported by languagetool (#6069) | 2021-08-15T19:59:09 | [3e4c519004a4](https://github.com/tldr-pages/tldr/commit/3e4c519004a471c861cdc609fd7239ee3355671c)
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | multiple pages: format technical tokens (#5119) Co-authored-by: bl-ue <54780737+bl-ue@users.noreply.github.com> Co-authored-by: [...] | 2021-01-31T18:05:18 | [a5fe31bc47ae](https://github.com/tldr-pages/tldr/commit/a5fe31bc47aece3efa5e66b52b3cf384f27d5d72)
[Owen Voke](mailto:owzie123@gmail.com) | wapm: add page (#3808) * wapm: add page * wapm: apply review comments | 2020-02-01T12:58:26 | [797ef1c201ce](https://github.com/tldr-pages/tldr/commit/797ef1c201ce61ac55290f97b0849f1fdec5b7e1)

