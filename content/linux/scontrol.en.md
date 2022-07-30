---
author: ['Nikhil Reddy']
date: 1602713774
title: "scontrol"
description: "scontrol, View information about and modify jobs."
categories: "linux"
---
> More information: <https://slurm.schedmd.com/scontrol.html>.

- Show information for job:

```bash
scontrol show job job_id
```

- Suspend a comma-separated list of running jobs:

```bash
scontrol suspend job_id
```

- Resume a comma-separated list of suspended jobs:

```bash
scontrol resume job_id
```

- Hold a comma-separated list of queued jobs (Use `release` command to permit the jobs to be scheduled):

```bash
scontrol hold job_id
```

- Release a comma-separated list of suspended job:

```bash
scontrol release job_id
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Nikhil Reddy](mailto:35285981+npalladium@users.noreply.github.com) | sstat, scontrol: add page (#4689) | 2020-10-15T00:16:14 | [fbfe2c201a84](https://github.com/tldr-pages/tldr/commit/fbfe2c201a848d17c8ee3c3e0830475b3a8c9325)

