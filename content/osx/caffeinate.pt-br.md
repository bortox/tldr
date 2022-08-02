---
author: ['Andréia Bohner']
date: 1659378325
title: "caffeinate"
description: "caffeinate, Evita que o macOS entre em suspensão (repouso)."
categories: "osx"
---
> Mais informações: <https://ss64.com/osx/caffeinate.html>.

- Evita a suspensão por uma hora (3600 segundos):

```bash
caffeinate -u -t 3600
```

- Evita a suspensão até que um comando seja concluído:

```bash
caffeinate -s "comando"
```

- Evita a suspensão até que você digite Ctrl-C:

```bash
caffeinate -i
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Andréia Bohner](mailto:andreiabohner@gmail.com) | osx/*: add pt_BR translations (#8269) | 2022-08-01T20:25:25 | [97b386939aa5](https://github.com/tldr-pages/tldr/commit/97b386939aa505be651794a55d3bea20b4f14ab2)

