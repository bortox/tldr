---
author: ['pxgamer', 'Ivan Aracki']
date: 1559788968
title: "kompose"
description: "kompose, A tool to convert docker-compose applications to Kubernetes."
categories: "common"
---
> More information: <https://github.com/kubernetes/kompose>.

- Deploy a dockerized application to Kubernetes:

```bash
kompose up -f docker-compose.yml
```

- Delete instantiated services/deployments from Kubernetes:

```bash
kompose down -f docker-compose.yml
```

- Convert a docker-compose file into Kubernetes resources file:

```bash
kompose convert -f docker-compose.yml
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[pxgamer](mailto:owzie123@gmail.com) | kompose: add link to homepage | 2019-06-06T04:42:48 | [bbaf4b3db5c3](https://github.com/tldr-pages/tldr/commit/bbaf4b3db5c391e5e37249db387223debad70b3b)
[Ivan Aracki](mailto:aracki.ivan@gmail.com) | kompose: add page (#2622) | 2018-12-01T12:33:03 | [d379634c5770](https://github.com/tldr-pages/tldr/commit/d379634c577055f2de13ccd29d6a7bbe3d18b9c7)

