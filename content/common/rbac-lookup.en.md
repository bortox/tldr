---
author: ['Ivan Aracki']
date: 1562360428
title: "rbac-lookup, TLDR Pages"
description: "rbac-lookup, Find roles and cluster roles attached to any user, service account or group name in your Kubernetes cluster."
categories: "common"
---
> More information: <https://github.com/reactiveops/rbac-lookup>.

- View all RBAC bindings:

```bash
rbac-lookup
```

- View RBAC bindings that match a given expression:

```bash
rbac-lookup search_term
```

- View all RBAC bindings along with the source role binding:

```bash
rbac-lookup -o wide
```

- View all RBAC bindings filtered by subject:

```bash
rbac-lookup -k user|group|serviceaccount
```

- View all RBAC bindings along with IAM roles (if you are using GKE):

```bash
rbac-lookup --gke
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Ivan Aracki](mailto:aracki.ivan@gmail.com) | rbac-lookup: add page (#3165) | 2019-07-05T23:00:28 | [945a4bd35e41](https://github.com/tldr-pages/tldr/commit/945a4bd35e414f1145b5189618253d8e93e9dd86)

