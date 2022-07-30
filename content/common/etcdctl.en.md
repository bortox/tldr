---
author: ['bl-ue']
date: 1621541621
title: "etcdctl"
description: "etcdctl, CLI interface for interacting with etcd, a highly-available key-value pair store."
categories: "common"
---
> More information: <https://etcd.io/docs/latest/dev-guide/interacting_v3/>.

- Display the value associated with a specified key:

```bash
etcdctl get my/key
```

- Store a key-value pair:

```bash
etcdctl put my/key my_value
```

- Delete a key-value pair:

```bash
etcdctl del my/key
```

- Store a key-value pair, reading the value from a file:

```bash
etcdctl put my/file < path/to/file.txt
```

- Save a snapshot of the etcd keystore:

```bash
etcdctl snapshot save path/to/snapshot.db
```

- Restore a snapshot of an etcd keystore (restart the etcd server afterwards):

```bash
etcdctl snapshot restore path/to/snapshot.db
```

- Add a user:

```bash
etcdctl user add my_user
```

- Watch a key for changes:

```bash
etcdctl watch my/key
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | *: fix typos reported by Hunspell (#5848) Co-authored-by: marchersimon <50295997+marchersimon@users.noreply.github.com> Co-authored- [...] | 2021-05-20T22:13:41 | [8ebd171d6f00](https://github.com/tldr-pages/tldr/commit/8ebd171d6f001698709fefc02b1fd5cc9f3a99c4)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | etcdctl: add page (#5006) | 2020-12-11T22:29:31 | [244a7b1c707c](https://github.com/tldr-pages/tldr/commit/244a7b1c707ca3853ab2aa6d9509352d21ba0023)

