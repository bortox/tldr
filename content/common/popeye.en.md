---
author: ['Marco Bonelli', 'Ivan Aracki']
date: 1559564381
title: "popeye, TLDR Pages"
description: "popeye, Utility that reports potential issues with Kubernetes deployment manifests."
categories: "common"
---
> More information: <https://github.com/derailed/popeye>.

- Scan the current Kubernetes cluster:

```bash
popeye
```

- Scan a specific namespace:

```bash
popeye -n namespace
```

- Scan specific Kubernetes context:

```bash
popeye --context=context
```

- Use a spinach configuration file for scanning:

```bash
popeye -f spinach.yaml
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Marco Bonelli](mailto:marco@mebeim.net) | Refactor: reword English pages' links' descriptions. | 2019-06-03T14:19:41 | [66abb98ce935](https://github.com/tldr-pages/tldr/commit/66abb98ce935c0f4516bf30c4d6da72180d5a3ab)
[Ivan Aracki](mailto:aracki.ivan@gmail.com) | popeye: add page (#3017) | 2019-05-14T20:47:47 | [00eb38b527b5](https://github.com/tldr-pages/tldr/commit/00eb38b527b5b0b11c5b19eafd80260eac8ba93d)

