---
author: ['Axel Navarro']
date: 1618586885
title: "gh run, TLDR Pages"
description: "gh run, View, run and watch recent GitHub Actions workflow runs."
categories: "common"
---
> More information: <https://cli.github.com/manual/gh_run>.

- Interactively select a run to see information about the jobs:

```bash
gh run view
```

- Display information about a specific run:

```bash
gh run view workflow_run_number
```

- Display information about the steps of a job:

```bash
gh run view --job=job_number
```

- Display the log of a job:

```bash
gh run view --job=job_number --log
```

- Check a specific workflow and exit with a non-zero status if the run failed:

```bash
gh run view workflow_run_number --exit-status && echo "run pending or passed"
```

- Interactively select an active run and wait until it's done:

```bash
gh run watch
```

- Display the jobs for a run and wait until it's done:

```bash
gh run watch workflow_run_number
```

- Re-run a specific workflow:

```bash
gh run rerun workflow_run_number
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Axel Navarro](mailto:navarroaxel@gmail.com) | gh-run: add page (#5766) | 2021-04-16T17:28:05 | [985b051569ed](https://github.com/tldr-pages/tldr/commit/985b051569ed6a1fb355af6b9c5922612f603bed)

