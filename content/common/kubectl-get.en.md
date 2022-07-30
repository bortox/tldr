---
author: ['Nelson Figueroa']
date: 1635042043
title: "kubectl get"
description: "kubectl get, Get Kubernetes objects and resources."
categories: "common"
---
> More information: <https://kubernetes.io/docs/reference/generated/kubectl/kubectl-commands#get>.

- Get all namespaces in the current cluster:

```bash
kubectl get namespaces
```

- Get nodes in a specified namespace:

```bash
kubectl get nodes -n namespace
```

- Get pods in a specified namespace:

```bash
kubectl get pods -n namespace
```

- Get deployments in a specified namespace:

```bash
kubectl get deployments -n namespace
```

- Get services in a specified namespace:

```bash
kubectl get services -n namespace
```

- Get all resources in a specified namespace:

```bash
kubectl get all -n namespace
```

- Get Kubernetes objects defined in a YAML manifest:

```bash
kubectl get -f path/to/manifest.yaml
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Nelson Figueroa](mailto:30811275+nelsonfigueroa@users.noreply.github.com) | kubectl-get: add get all example (#7043) | 2021-10-24T04:20:43 | [c99cc4e254b1](https://github.com/tldr-pages/tldr/commit/c99cc4e254b12efaa835edb268bf6b30ad484296)
[Nelson Figueroa](mailto:30811275+nelsonfigueroa@users.noreply.github.com) | kubectl-get: add page (#4488) | 2020-10-05T17:08:22 | [c86aa251bdd4](https://github.com/tldr-pages/tldr/commit/c86aa251bdd44dbf579125d24807124d47ce7b46)

