---
author: ['Rodrigo Nemmen']
date: 1643507859
title: "progress, TLDR Pages"
description: "progress, Display/Monitor the progress of running coreutils."
categories: "common"
---
> More information: <https://github.com/Xfennec/progress>.

- Show the progress of running coreutils:

```bash
progress
```

- Show the progress of running coreutils in quiet mode:

```bash
progress -q
```

- Launch and monitor a single long-running command:

```bash
command & progress --monitor --pid $!
```

- Include an estimate of time remaining for completion:

```bash
progress --wait --command firefox
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Rodrigo Nemmen](mailto:rodrigo.nemmen@iag.usp.br) | progress: add page (#7510) | 2022-01-30T02:57:39 | [9ad2a08a7311](https://github.com/tldr-pages/tldr/commit/9ad2a08a73116dbacb50fb4dc3afce3742fc19bf)

