---
author: ['oshiteku', 'Nelson Figueroa']
date: 1645329568
title: "kubectl delete, TLDR Pages"
description: "kubectl delete, Delete Kubernetes resources."
categories: "common"
---
> More information: <https://kubernetes.io/docs/reference/generated/kubectl/kubectl-commands#delete>.

- Delete a specific pod:

```bash
kubectl delete pod pod_name
```

- Delete a specific deployment:

```bash
kubectl delete deployment deployment_name
```

- Delete a specific node:

```bash
kubectl delete node node_name
```

- Delete all pods in a specified namespace:

```bash
kubectl delete pods --all --namespace namespace
```

- Delete all deployments and services in a specified namespace:

```bash
kubectl delete deployments,services --all --namespace namespace
```

- Delete all nodes:

```bash
kubectl delete nodes --all
```

- Delete resources defined in a YAML manifest:

```bash
kubectl delete --filename path/to/manifest.yaml
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[oshiteku](mailto:65475078+oshiteku@users.noreply.github.com) | kubectl-delete: fix typo (#7804) | 2022-02-20T04:59:28 | [4cc80092f933](https://github.com/tldr-pages/tldr/commit/4cc80092f933fcc5eeaa5223e96d22a38f95b47a)
[Nelson Figueroa](mailto:30811275+nelsonfigueroa@users.noreply.github.com) | kubectl-delete: add page (#7042) | 2021-10-24T14:15:36 | [be8f21e02f71](https://github.com/tldr-pages/tldr/commit/be8f21e02f71a73ee37e0b9a0982f360da9c4ddf)

