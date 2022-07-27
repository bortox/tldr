---
author: ['Nikhil Reddy']
date: 1602713774
title: "sstat, TLDR Pages"
description: "sstat, View information about running jobs."
categories: "linux"
---
> More information: <https://slurm.schedmd.com/sstat.html>.

- Display status information of a comma-separated list of jobs:

```bash
sstat --jobs=job_id
```

- Display job ID, average CPU and average virtual memory size of a comma-separated list of jobs, with pipes as column delimiters:

```bash
sstat --parsable --jobs=job_id --format=JobID,AveCPU,AveVMSize
```

- Display list of fields available:

```bash
sstat --helpformat
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Nikhil Reddy](mailto:35285981+npalladium@users.noreply.github.com) | sstat, scontrol: add page (#4689) | 2020-10-15T00:16:14 | [fbfe2c201a84](https://github.com/tldr-pages/tldr/commit/fbfe2c201a848d17c8ee3c3e0830475b3a8c9325)

