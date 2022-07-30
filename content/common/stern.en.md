---
author: ['Ivan Aracki']
date: 1562068654
title: "stern"
description: "stern, Tail multiple pods and containers from Kubernetes."
categories: "common"
---
> More information: <https://github.com/wercker/stern/>.

- Tail all pods within a current namespace:

```bash
stern .
```

- Tail all pods with a specific status:

```bash
stern . --container-state running|waiting|terminated
```

- Tail all pods that matches a given regular expression:

```bash
stern pod_query
```

- Tail matched pods from all namespaces:

```bash
stern pod_query --all-namespaces
```

- Tail matched pods from 15 minutes ago:

```bash
stern pod_query --since 15m
```

- Tail matched pods with a specific label:

```bash
stern pod_query --selector release=canary
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Ivan Aracki](mailto:aracki.ivan@gmail.com) | stern: add page (#3159) | 2019-07-02T13:57:34 | [4445f79eb505](https://github.com/tldr-pages/tldr/commit/4445f79eb505774ea4d037a3d129ab5c8c7a29a4)

