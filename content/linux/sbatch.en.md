---
author: ['Garrett Mills', 'Emily Grace Seville']
date: 1647882468
title: "sbatch"
description: "sbatch, Submit a batch job to the SLURM scheduler."
categories: "linux"
---
> More information: <https://manned.org/sbatch>.

- Submit a batch job:

```bash
sbatch path/to/job.sh
```

- Submit a batch job with a custom name:

```bash
sbatch --job-name=myjob path/to/job.sh
```

- Submit a batch job with a time limit of 30 minutes:

```bash
sbatch --time=00:30:00 path/to/job.sh
```

- Submit a job and request multiple nodes:

```bash
sbatch --nodes=3 path/to/job.sh
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Emily Grace Seville](mailto:emilyseville7cf@gmail.com) | linux/*: add more information link (#7848) | 2022-03-21T18:07:48 | [4659bcb243ac](https://github.com/tldr-pages/tldr/commit/4659bcb243ac572c9e0c95117097801f1e62bda4)
[Garrett Mills](mailto:garrett@glmdev.tech) | sbatch: add page (#2584) | 2018-11-14T07:34:46 | [0b0d5a3cce92](https://github.com/tldr-pages/tldr/commit/0b0d5a3cce92d63a79da9cb0ae04b1c3525526a5)

