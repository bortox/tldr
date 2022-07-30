---
author: ['Nelson Figueroa']
date: 1634181585
title: "kubectl logs"
description: "kubectl logs, Show logs for containers in a pod."
categories: "common"
---
> More information: <https://kubernetes.io/docs/reference/generated/kubectl/kubectl-commands#logs>.

- Show logs for a single-container pod:

```bash
kubectl logs pod_name
```

- Show logs for a specified container in a pod:

```bash
kubectl logs --container container_name pod_name
```

- Show logs for all containers in a pod:

```bash
kubectl logs --all-containers=true pod_name
```

- Stream pod logs:

```bash
kubectl logs --follow pod_name
```

- Stream logs for a specified container in a pod:

```bash
kubectl logs --follow --container container_name pod_name
```

- Show pod logs newer than a relative time like `10s`, `5m`, or `1h`:

```bash
kubectl logs --since=relative_time pod_name
```

- Show the 10 most recent logs in a pod:

```bash
kubectl logs --tail=10 pod_name
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Nelson Figueroa](mailto:30811275+nelsonfigueroa@users.noreply.github.com) | kubectl-logs: add page (#6665) | 2021-10-14T05:19:45 | [726f0647059e](https://github.com/tldr-pages/tldr/commit/726f0647059ee809938e5326d13f16958e2e75f0)

