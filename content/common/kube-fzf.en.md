---
author: ['pxgamer', 'Nithya', 'bl-ue']
date: 1621541621
title: "kube-fzf, TLDR Pages"
description: "kube-fzf, Shell commands for command-line fuzzy searching of Kubernetes Pods."
categories: "common"
---
> See also `kubectl` for related commands.

> More information: <https://github.com/thecasualcoder/kube-fzf>.

- Get pod details (from current namespace):

```bash
findpod
```

- Get pod details (from all namespaces):

```bash
findpod -a
```

- Describe a pod:

```bash
describepod
```

- Tail pod logs:

```bash
tailpod
```

- Exec into a pod's container:

```bash
execpod shell_command
```

- Port-forward a pod:

```bash
pfpod port_number
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | *: fix typos reported by Hunspell (#5848) Co-authored-by: marchersimon <50295997+marchersimon@users.noreply.github.com> Co-authored- [...] | 2021-05-20T22:13:41 | [8ebd171d6f00](https://github.com/tldr-pages/tldr/commit/8ebd171d6f001698709fefc02b1fd5cc9f3a99c4)
[pxgamer](mailto:owzie123@gmail.com) | kube-fzf: add link to homepage | 2019-06-06T04:42:48 | [82279b7ee5d7](https://github.com/tldr-pages/tldr/commit/82279b7ee5d7747b6226ee57559c8765c08594e9)
[Nithya](mailto:nithyanatarajn@gmail.com) | kube-fzf: add page (#2536) | 2018-11-12T02:37:37 | [2354d4304a2a](https://github.com/tldr-pages/tldr/commit/2354d4304a2a8a5a37181231d0f3e90e00824b3f)

