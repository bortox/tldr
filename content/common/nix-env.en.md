---
author: ['BlackGlory', 'Morgan Erlich', 'Aaron Janse', 'Ruben Vereecken', 'Zekai.Zheng', 'pxgamer', 'Americo']
date: 1609539158
title: "nix-env, TLDR Pages"
description: "nix-env, Manipulate or query Nix user environments."
categories: "common"
---
> More information: <https://nixos.org/manual/nix/stable/#sec-nix-env>.

- List all installed packages:

```bash
nix-env -q
```

- Query installed packages:

```bash
nix-env -q search_term
```

- Query available packages:

```bash
nix-env -qa search_term
```

- Install package:

```bash
nix-env -iA nixpkgs.pkg_name
```

- Install a package from a URL:

```bash
nix-env -i pkg_name --file example.com
```

- Uninstall package:

```bash
nix-env -e pkg_name
```

- Upgrade one package:

```bash
nix-env -u pkg_name
```

- Upgrade all packages:

```bash
nix-env -u
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Morgan Erlich](mailto:nagromlobo@gmail.com) | nix-shell, nix-env: add page and fix manual link (#5060) | 2021-01-01T23:12:38 | [ffa6317a54f3](https://github.com/tldr-pages/tldr/commit/ffa6317a54f3f83067f1c07fbe0205c2c6affa37)
[BlackGlory](mailto:woshenmedoubuzhidao@blackglory.me) | nix-env: fix example (#4108) | 2020-06-17T17:59:02 | [c564017f4505](https://github.com/tldr-pages/tldr/commit/c564017f4505184dbc5d431685904ea9f2fffc67)
[Americo](mailto:ame.zuz@gmail.com) | nix-env: add --file example | 2019-11-05T22:37:16 | [5ea2e7decf81](https://github.com/tldr-pages/tldr/commit/5ea2e7decf81090f24c8f63d92e40648d80dd2ba)
[pxgamer](mailto:owzie123@gmail.com) | nix-env: add link to homepage | 2019-06-04T21:29:40 | [ee2ed54c6d94](https://github.com/tldr-pages/tldr/commit/ee2ed54c6d944299ca675d21ab7169035abc27c4)
[Aaron Janse](mailto:aaron@ajanse.me) | nix-env: improve page (#2807) - add example showing installed packages - replace status example with one for searching within [...] | 2019-02-28T17:50:42 | [2fe076283366](https://github.com/tldr-pages/tldr/commit/2fe07628336680aa164a34c4e52c5634c5f4a049)
[Ruben Vereecken](mailto:rubenvereecken@gmail.com) | Formatted and cut away 3 examples from nix-env | 2016-01-25T00:15:36 | [98c99b155878](https://github.com/tldr-pages/tldr/commit/98c99b155878d9b5dd9dd9aa823defa4ce438b64)
[Zekai.Zheng](mailto:zekai.zheng@tabcorp.com.au) | Add the nix-env for common | 2016-01-25T00:15:36 | [745a0ddca7a2](https://github.com/tldr-pages/tldr/commit/745a0ddca7a2ba039d7cbf8e7822e7aa0c6d2769)

