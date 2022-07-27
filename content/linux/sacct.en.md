---
author: ['Caughlin Bohn']
date: 1602587346
title: "sacct, TLDR Pages"
description: "sacct, Display accounting data from the Slurm service."
categories: "linux"
---
> More information: <https://slurm.schedmd.com/sacct.html>.

- Display job id, job name, partition, account, number of allocated cpus, job state, and job exit codes for recent jobs:

```bash
sacct
```

- Display job id, job state, job exit code for recent jobs:

```bash
sacct --brief
```

- Display the allocations of a job:

```bash
sacct --jobs job_id --allocations
```

- Display elapsed time, job name, number of requested CPUs, and memory requested of a job:

```bash
sacct --jobs job_id --format=elapsed,jobname,reqcpus,reqmem
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Caughlin Bohn](mailto:35080828+cbohn4@users.noreply.github.com) | sacct, scancel, srun: add page (#4600) | 2020-10-13T13:09:06 | [91fd12324185](https://github.com/tldr-pages/tldr/commit/91fd12324185bd403faffa3c2712cd739c2b8d53)

