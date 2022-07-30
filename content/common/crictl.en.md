---
author: ['yanhuan']
date: 1656489621
title: "crictl"
description: "crictl, Command-line for CRI-compatible container runtimes."
categories: "common"
---
> More information: <https://github.com/kubernetes-sigs/cri-tools/blob/master/docs/crictl.md>.

- List all kubernetes pods (Ready and NotReady):

```bash
crictl pods
```

- List all containers (Running and Exited):

```bash
crictl ps --all
```

- List all images:

```bash
crictl images
```

- Print information about specific containers:

```bash
crictl inspect container_id1 container_id2 ...
```

- Open a specific shell inside a running container:

```bash
crictl exec -it container_id sh
```

- Pull a specific image from a registry:

```bash
crictl pull image:tag
```

- Print and [f]ollow logs of a specific container:

```bash
crictl logs -f container_id
```

- Remove one or more images:

```bash
crictl rmi image_id1 image_id2 ...
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[yanhuan](mailto:53329052+yanhuan0802@users.noreply.github.com) | crictl: add page (#8152) | 2022-06-29T10:00:21 | [32ddd0d9a720](https://github.com/tldr-pages/tldr/commit/32ddd0d9a7209275d622693c7e63903de41a892a)

