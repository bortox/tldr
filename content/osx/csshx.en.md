---
author: ['bl-ue', 'Emily Grace Seville']
date: 1644837703
title: "csshX, TLDR Pages"
description: "csshX, Cluster SSH tool for macOS."
categories: "osx"
---
> More information: <https://github.com/brockgr/csshx>.

- Connect to multiple hosts:

```bash
csshX hostname1 hostname2
```

- Connect to multiple hosts with a given SSH key:

```bash
csshX user@hostname1 user@hostname2 --ssh_args "-i path/to/ssh_key.pem"
```

- Connect to a pre-defined cluster from `/etc/clusters`:

```bash
csshX cluster1
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Emily Grace Seville](mailto:emilyseville7cf@gmail.com) | osx/*: update page (#7665) | 2022-02-14T12:21:43 | [692469016e62](https://github.com/tldr-pages/tldr/commit/692469016e62d4410ec92a8f29272e447046a0d2)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | *: fix typos reported by Hunspell (#5848) Co-authored-by: marchersimon <50295997+marchersimon@users.noreply.github.com> Co-authored- [...] | 2021-05-20T22:13:41 | [8ebd171d6f00](https://github.com/tldr-pages/tldr/commit/8ebd171d6f001698709fefc02b1fd5cc9f3a99c4)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | csshX: rename to csshx (#5384) | 2021-03-09T14:29:08 | [d5c493d866c0](https://github.com/tldr-pages/tldr/commit/d5c493d866c0459515b7f54400a169113cabcd38)

