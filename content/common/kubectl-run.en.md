---
author: ['Matt Cristantello']
date: 1624650792
title: "kubectl run, TLDR Pages"
description: "kubectl run, Run pods in Kubernetes. Specifies pod generator to avoid deprecation error in some K8S versions."
categories: "common"
---
> More information: <https://kubernetes.io/docs/reference/generated/kubectl/kubectl-commands#run>.

- Run an nginx pod and expose port 80:

```bash
kubectl run --generator=run-pod/v1 nginx --image=nginx --port 80
```

- Run an nginx pod, setting the TEST_VAR environment variable:

```bash
kubectl run --generator=run-pod/v1 nginx --image=nginx --env="TEST_VAR=testing"
```

- Show API calls that would be made to create an nginx container:

```bash
kubectl run --generator=run-pod/v1 nginx --image=nginx --dry-run
```

- Run an Ubuntu pod interactively, never restart it, and remove it when it exits:

```bash
kubectl run --generator=run-pod/v1 -it temp-ubuntu --image=ubuntu:20.04 --restart=Never --rm -- /bin/bash
```

- Run an Ubuntu pod, overriding the default command with echo, and specifying custom arguments:

```bash
kubectl run --generator=run-pod/v1 temp-ubuntu --image=ubuntu:20.04 --command -- echo arg1 arg2 arg3
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Matt Cristantello](mailto:matt@cristantello.com) | kubectl-run: add page (#6161) | 2021-06-25T21:53:12 | [9619f7a3ba35](https://github.com/tldr-pages/tldr/commit/9619f7a3ba356b4e9cae0137750529132acefd89)

