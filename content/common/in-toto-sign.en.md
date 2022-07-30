---
author: ['Furkan']
date: 1634756728
title: "in-toto-sign"
description: "in-toto-sign, Sign in-toto link or layout metadata or verify their signatures."
categories: "common"
---
> More information: <https://in-toto.readthedocs.io/en/latest/command-line-tools/in-toto-sign.html>.

- Sign 'unsigned.layout' with two keys and write it to 'root.layout':

```bash
in-toto-sign -f unsigned.layout -k priv_key1 priv_key2 -o root.layout
```

- Replace signature in link file and write to default filename:

```bash
in-toto-sign -f package.2f89b927.link -k priv_key
```

- Verify a layout signed with 3 keys:

```bash
in-toto-sign -f root.layout -k pub_key0 pub_key1 pub_key2 --verify
```

- Sign a layout with the default GPG key in default GPG keyring:

```bash
in-toto-sign -f root.layout --gpg
```

- Verify a layout with a GPG key identified by keyid '...439F3C2':

```bash
in-toto-sign -f root.layout --verify --gpg ...439F3C2
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Furkan](mailto:furkan.turkal@trendyol.com) | in-toto-sign: add page | 2021-10-20T21:05:28 | [fdf906e609e7](https://github.com/tldr-pages/tldr/commit/fdf906e609e7e380262ad375a425ff33cc68447c)

