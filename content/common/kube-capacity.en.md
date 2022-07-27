---
author: ['Marco Bonelli', 'Ivan Aracki']
date: 1559564381
title: "kube-capacity, TLDR Pages"
description: "kube-capacity, A simple CLI that provides an overview of the resource requests, limits, and utilization in a Kubernetes cluster."
categories: "common"
---
> Combine the best parts of `kubectl top` and `kubectl describe` into a CLI focused on cluster resources.

> More information: <https://github.com/robscott/kube-capacity>.

- Output a list of nodes with the total CPU and Memory resource requests and limits:

```bash
kube-capacity
```

- Include pods:

```bash
kube-capacity -p
```

- Include utilization:

```bash
kube-capacity -u
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Marco Bonelli](mailto:marco@mebeim.net) | Refactor: reword English pages' links' descriptions. | 2019-06-03T14:19:41 | [66abb98ce935](https://github.com/tldr-pages/tldr/commit/66abb98ce935c0f4516bf30c4d6da72180d5a3ab)
[Ivan Aracki](mailto:aracki.ivan@gmail.com) | kube-capacity: add page (#2864) | 2019-04-04T20:43:55 | [f9064de1ebf3](https://github.com/tldr-pages/tldr/commit/f9064de1ebf3ae5b4d1282e99d7d0d8f59386dee)

