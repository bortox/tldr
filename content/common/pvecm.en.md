---
author: ['Ein Verne']
date: 1636318211
title: "pvecm, TLDR Pages"
description: "pvecm, Proxmox VE Cluster Manager."
categories: "common"
---
> More information: <https://pve.proxmox.com/pve-docs/pvecm.1.html>.

- Add the current node to an existing cluster:

```bash
pvecm add hostname_or_ip
```

- Add a node to the cluster configuration (internal use):

```bash
pvecm addnode node
```

- Return the version of the cluster join API available on this node:

```bash
pvecm apiver
```

- Generate new cluster configuration:

```bash
pvecm create clustername
```

- Remove a node from the cluster configuration:

```bash
pvecm delnode node
```

- Display the local view of the cluster nodes:

```bash
pvecm nodes
```

- Display the local view of the cluster status:

```bash
pvecm status
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Ein Verne](mailto:einverne@gmail.com) | pvecm: add page (#7214) | 2021-11-07T21:50:11 | [35065c3889bf](https://github.com/tldr-pages/tldr/commit/35065c3889bfd4032ff0631c87747f3b0e03244e)

