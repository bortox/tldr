---
author: ['Caughlin Bohn']
date: 1602587346
title: "srun"
description: "srun, Create an interactive slurm job or connect to an existing job."
categories: "linux"
---
> More information: <https://slurm.schedmd.com/srun.html>.

- Submit a basic interactive job:

```bash
srun --pty /bin/bash
```

- Submit an interactive job with different attributes:

```bash
srun --ntasks-per-node=num_cores --mem-per-cpu=memory_MB --pty /bin/bash
```

- Connect to a worker node with a job running:

```bash
srun --jobid=job_id --pty /bin/bash
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Caughlin Bohn](mailto:35080828+cbohn4@users.noreply.github.com) | sacct, scancel, srun: add page (#4600) | 2020-10-13T13:09:06 | [91fd12324185](https://github.com/tldr-pages/tldr/commit/91fd12324185bd403faffa3c2712cd739c2b8d53)

