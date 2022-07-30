---
author: ['Guido Lena Cota', 'Thamaraiselvam']
date: 1604238005
title: "kind"
description: "kind, Tool for running local Kubernetes clusters using Docker container 'nodes'."
categories: "common"
---
> Designed for testing Kubernetes itself, but may be used for local development or continuous integration.

> More information: <https://github.com/kubernetes-sigs/kind>.

- Create a local Kubernetes cluster:

```bash
kind create cluster --name cluster_name
```

- Delete one or more clusters:

```bash
kind delete clusters cluster_name
```

- Get details about clusters, nodes, or the kubeconfig:

```bash
kind get clusters|nodes|kubeconfig
```

- Export the kubeconfig or the logs:

```bash
kind export kubeconfig|logs
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Guido Lena Cota](mailto:guido.lenacota@gmail.com) | multiple pages: Use snake_case in token syntax (#4788) | 2020-11-01T14:40:05 | [0bb9c353a717](https://github.com/tldr-pages/tldr/commit/0bb9c353a717513283f8cda8493e5370ca47219a)
[Thamaraiselvam](mailto:thamaraiselvam@live.com) | kind: add page (#4394) | 2020-10-06T13:25:24 | [bd38407b568d](https://github.com/tldr-pages/tldr/commit/bd38407b568d114b847e3ec2091f88bc90ea6585)

