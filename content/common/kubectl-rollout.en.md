---
author: ['Nelson Figueroa']
date: 1634181657
title: "kubectl rollout"
description: "kubectl rollout, Manage the rollout of a Kubernetes resource (deployments, daemonsets, and statefulsets)."
categories: "common"
---
> More information: <https://kubernetes.io/docs/reference/generated/kubectl/kubectl-commands#rollout>.

- Start a rolling restart of a resource:

```bash
kubectl rollout restart resource_type/resource_name
```

- Watch the rolling update status of a resource:

```bash
kubectl rollout status resource_type/resource_name
```

- Roll back a resource to the previous revision:

```bash
kubectl rollout undo resource_type/resource_name
```

- View the rollout history of a resource:

```bash
kubectl rollout history resource_type/resource_name
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Nelson Figueroa](mailto:30811275+nelsonfigueroa@users.noreply.github.com) | kubectl-rollout: add page (#6671) | 2021-10-14T05:20:57 | [96a3bb8dc80b](https://github.com/tldr-pages/tldr/commit/96a3bb8dc80b0ba80ecf3e52d43943ee0f710ee7)

