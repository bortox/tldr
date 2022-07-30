---
author: ['Nicolas Hansse']
date: 1633555451
title: "fluxctl"
description: "fluxctl, Command-line tool for Flux v1."
categories: "common"
---
> More information: <https://fluxcd.io/legacy/flux/references/fluxctl>.

- List workloads currently running in the cluster on specific namespace:

```bash
fluxctl --k8s-fwd-ns=namespace list-workloads
```

- Show deployed and available images:

```bash
fluxctl list-images
```

- Synchronize the cluster with the git repository:

```bash
fluxctl sync
```

- Turn on automatic deployment for a workload:

```bash
fluxctl automate
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Nicolas Hansse](mailto:nico.hansse@gmail.com) | fluxctl: add page (#6814) | 2021-10-06T23:24:11 | [575792203c1b](https://github.com/tldr-pages/tldr/commit/575792203c1b4c3893cda3634c3600fad13701e1)

