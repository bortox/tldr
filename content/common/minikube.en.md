---
author: ['Nelson Figueroa', 'bl-ue', 'pxgamer', 'Edson Celio']
date: 1621541621
title: "minikube"
description: "minikube, Tool to run Kubernetes locally."
categories: "common"
---
> More information: <https://github.com/kubernetes/minikube>.

- Start the cluster:

```bash
minikube start
```

- Get the IP address of the cluster:

```bash
minikube ip
```

- Access a service named my_service exposed via a node port and get the URL:

```bash
minikube service my_service --url
```

- Open the Kubernetes dashboard in a browser:

```bash
minikube dashboard
```

- Stop the running cluster:

```bash
minikube stop
```

- Delete the cluster:

```bash
minikube delete
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | *: fix typos reported by Hunspell (#5848) Co-authored-by: marchersimon <50295997+marchersimon@users.noreply.github.com> Co-authored- [...] | 2021-05-20T22:13:41 | [8ebd171d6f00](https://github.com/tldr-pages/tldr/commit/8ebd171d6f001698709fefc02b1fd5cc9f3a99c4)
[Nelson Figueroa](mailto:30811275+nelsonfigueroa@users.noreply.github.com) | minikube: add stop, delete (#4384) | 2020-10-01T12:37:26 | [b8b451e0fc09](https://github.com/tldr-pages/tldr/commit/b8b451e0fc0968f29aea009bd2d5e4d7da3ab2f8)
[pxgamer](mailto:owzie123@gmail.com) | minikube: add link to homepage | 2019-06-04T21:29:40 | [f845c64d0899](https://github.com/tldr-pages/tldr/commit/f845c64d0899acb1c8d3b4fa0962f0d23ffe3e56)
[Edson Celio](mailto:edsoncelio@users.noreply.github.com) | minikube: add page (#2358) | 2018-10-01T18:27:58 | [7391a4acff1b](https://github.com/tldr-pages/tldr/commit/7391a4acff1bcc3f6b62d2ab8cda538dbb8c2952)

