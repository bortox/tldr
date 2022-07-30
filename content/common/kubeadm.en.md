---
author: ['Will Hegedus', 'bl-ue', 'pxgamer']
date: 1621541621
title: "kubeadm"
description: "kubeadm, Command-line interface for creating and managing Kubernetes clusters."
categories: "common"
---
> More information: <https://kubernetes.io/docs/reference/setup-tools/kubeadm>.

- Create a Kubernetes master node:

```bash
kubeadm init
```

- Bootstrap a Kubernetes worker node and join it to a cluster:

```bash
kubeadm join --token token
```

- Create a new bootstrap token with a TTL of 12 hours:

```bash
kubeadm token create --ttl 12h0m0s
```

- Check if the Kubernetes cluster is upgradeable and which versions are available:

```bash
kubeadm upgrade plan
```

- Upgrade Kubernetes cluster to a specified version:

```bash
kubeadm upgrade apply version
```

- View the kubeadm ConfigMap containing the cluster's configuration:

```bash
kubeadm config view
```

- Revert changes made to the host by 'kubeadm init' or 'kubeadm join':

```bash
kubeadm reset
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | *: fix typos reported by Hunspell (#5848) Co-authored-by: marchersimon <50295997+marchersimon@users.noreply.github.com> Co-authored- [...] | 2021-05-20T22:13:41 | [8ebd171d6f00](https://github.com/tldr-pages/tldr/commit/8ebd171d6f001698709fefc02b1fd5cc9f3a99c4)
[pxgamer](mailto:owzie123@gmail.com) | kubeadm: add link to homepage | 2019-06-06T04:42:48 | [0e66f1e2660f](https://github.com/tldr-pages/tldr/commit/0e66f1e2660f7576f203450d8c90c00ec43c0247)
[Will Hegedus](mailto:wbhegedus@gmail.com) | kubeadm: add page (#2495) | 2018-10-31T01:29:20 | [682b8409be0e](https://github.com/tldr-pages/tldr/commit/682b8409be0ee345d6c35890af6ded672e05ea28)

