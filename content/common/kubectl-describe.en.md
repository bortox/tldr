---
author: ['Nelson Figueroa']
date: 1601910576
title: "kubectl describe"
description: "kubectl describe, Show details of Kubernetes objects and resources."
categories: "common"
---
> More information: <https://kubernetes.io/docs/reference/generated/kubectl/kubectl-commands#describe>.

- Show details of pods in a namespace:

```bash
kubectl describe pods -n namespace
```

- Show details of nodes in a namespace:

```bash
kubectl describe nodes -n namespace
```

- Show the details of a specific pod in a namespace:

```bash
kubectl describe pods pod_name -n namespace
```

- Show the details of a specific node in a namespace:

```bash
kubectl describe nodes node_name -n namespace
```

- Show details of Kubernetes objects defined in a YAML manifest:

```bash
kubectl describe -f path/to/manifest.yaml
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Nelson Figueroa](mailto:30811275+nelsonfigueroa@users.noreply.github.com) | kubectl-describe: add page (#4494) | 2020-10-05T17:09:36 | [00c6193ce53c](https://github.com/tldr-pages/tldr/commit/00c6193ce53cc84b086385fbb16d82be59038e0e)

