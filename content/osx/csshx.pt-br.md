---
author: ['Andréia Bohner']
date: 1659378325
title: "csshX"
description: "csshX, Ferramenta de Cluster SSH para macOS."
categories: "osx"
---
> Mais informações: <https://github.com/brockgr/csshx>.

- Conecta a vários hosts:

```bash
csshX nomedohost1 nomedohost2
```

- Conecta a vários hosts com uma determinada chave SSH:

```bash
csshX user@nomedohost1 user@nomedohost2 --ssh_args "-i caminho/para/ssh_key.pem"
```

- Conecta a um cluster predefinido em `/etc/clusters`:

```bash
csshX cluster1
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Andréia Bohner](mailto:andreiabohner@gmail.com) | osx/*: add pt_BR translations (#8269) | 2022-08-01T20:25:25 | [97b386939aa5](https://github.com/tldr-pages/tldr/commit/97b386939aa505be651794a55d3bea20b4f14ab2)

