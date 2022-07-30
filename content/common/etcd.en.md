---
author: ['bl-ue']
date: 1621541621
title: "etcd"
description: "etcd, A distributed, reliable key-value store for the most critical data of a distributed system."
categories: "common"
---
> More information: <https://etcd.io>.

- Start a single-node etcd cluster:

```bash
etcd
```

- Start a single-node etcd cluster, listening for client requests on a custom URL:

```bash
etcd --advertise-client-urls http://127.0.0.1:1234 --listen-client-urls http://127.0.0.1:1234
```

- Start a single-node etcd cluster with a custom name:

```bash
etcd --name my_etcd_cluster
```

- Start a single-node etcd cluster with extensive metrics available at http://localhost:2379/debug/pprof/:

```bash
etcd --enable-pprof --metrics extensive
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | *: fix typos reported by Hunspell (#5848) Co-authored-by: marchersimon <50295997+marchersimon@users.noreply.github.com> Co-authored- [...] | 2021-05-20T22:13:41 | [8ebd171d6f00](https://github.com/tldr-pages/tldr/commit/8ebd171d6f001698709fefc02b1fd5cc9f3a99c4)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | etcd: add page (#5007) | 2020-12-12T21:07:25 | [051ce4819b54](https://github.com/tldr-pages/tldr/commit/051ce4819b543378f17b477bde5f2f2be6e81f40)

