---
author: ['Garrett Mills', 'Starbeamrainbowlabs']
date: 1577556206
title: "sinfo"
description: "sinfo, View information about Slurm nodes and partitions."
categories: "linux"
---
> See also `squeue` and `sbatch`, which are also part of the Slurm workload manager.

> More information: <https://slurm.schedmd.com/sinfo.html>.

- Show a quick summary overview of the cluster:

```bash
sinfo --summarize
```

- View the detailed status of all partitions across the entire cluster:

```bash
sinfo
```

- View the detailed status of a specific partition:

```bash
sinfo --partition partition_name
```

- View information about idle nodes:

```bash
sinfo --states idle
```

- Summarise dead nodes:

```bash
sinfo --dead
```

- List dead nodes and the reasons why:

```bash
sinfo --list-reasons
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Starbeamrainbowlabs](mailto:sbrl@starbeamrainbowlabs.com) | sinfo: add link and improve examples (#3700) | 2019-12-28T19:03:26 | [75d109448a21](https://github.com/tldr-pages/tldr/commit/75d109448a21c8bd82e6cc1f2912d8b0d2a8d631)
[Garrett Mills](mailto:garrett@glmdev.tech) | sinfo: add page (#2599) | 2018-11-21T18:05:57 | [724574333167](https://github.com/tldr-pages/tldr/commit/72457433316790974308ac0b5e83c38cb2b21383)

