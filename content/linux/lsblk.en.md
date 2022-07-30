---
author: ['Amine Hajyoussef', 'sbuller', 'Ein Verne', 'Lucas Gabriel Schneider', 'Gautam krishna.R', 'Ruben Vereecken']
date: 1629110041
title: "lsblk"
description: "lsblk, Lists information about devices."
categories: "linux"
---
> More information: <https://manned.org/lsblk>.

- List all storage devices in a tree-like format:

```bash
lsblk
```

- Also list empty devices:

```bash
lsblk -a
```

- Print the SIZE column in bytes rather than in a human-readable format:

```bash
lsblk -b
```

- Output info about filesystems:

```bash
lsblk -f
```

- Use ASCII characters for tree formatting:

```bash
lsblk -i
```

- Output info about block-device topology:

```bash
lsblk -t
```

- Exclude the devices specified by the comma-separated list of major device numbers:

```bash
lsblk -e 1,7
```

- Display a customized summary using a comma-separated list of columns:

```bash
lsblk --output NAME,SERIAL,MODEL,TRAN,TYPE,SIZE,FSTYPE,MOUNTPOINT
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | linux/[l-m]: add more information link (#6231) | 2021-08-16T12:34:01 | [41db1d238028](https://github.com/tldr-pages/tldr/commit/41db1d2380286234a89aaa2131d8e1d1c531b850)
[sbuller](mailto:stefan.buller@gmail.com) | lsblk: add custom output example (#5039) | 2020-12-22T12:59:32 | [2c80e464ba93](https://github.com/tldr-pages/tldr/commit/2c80e464ba93f675db5c39412c1d563247ef7fa9)
[Ein Verne](mailto:einverne@gmail.com) | lsblk, df: add exclude examples (#4086) | 2020-06-03T15:31:47 | [346abde565a7](https://github.com/tldr-pages/tldr/commit/346abde565a7281fc56ae5643239799b7a13e2cf)
[Amine Hajyoussef](mailto:hajyoussef.amine@gmail.com) | replace − with dash(-) | 2016-03-31T10:32:28 | [8b773ed6826b](https://github.com/tldr-pages/tldr/commit/8b773ed6826b8c7e82e71a1be8c6fa16670d2607)
[Ruben Vereecken](mailto:rubenvereecken@gmail.com) | Reformatted pages once more | 2016-01-13T12:04:46 | [967633411984](https://github.com/tldr-pages/tldr/commit/9676334119847078e5e05fec393a3fe36991dbc2)
[Gautam krishna.R](mailto:rgautamkrishna@gmail.com) | lsblk: add page | 2016-01-05T23:06:03 | [35616d762406](https://github.com/tldr-pages/tldr/commit/35616d762406bca865e557fd990f17123dc11b45)

