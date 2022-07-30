---
author: ['Reinhart Previano Koentjoro']
date: 1642352326
title: "glab pipeline"
description: "glab pipeline, List, view, and run GitLab CI/CD pipelines."
categories: "common"
---
> More information: <https://glab.readthedocs.io/en/latest/pipeline>.

- View a running pipeline on the current branch:

```bash
glab pipeline status
```

- View a running pipeline on a specific branch:

```bash
glab pipeline status --branch branch_name
```

- Get the list of pipelines:

```bash
glab pipeline list
```

- Run a manual pipeline on the current branch:

```bash
glab pipeline run
```

- Run a manual pipeline on a specific branch:

```bash
glab pipeline run --branch branch_name
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Reinhart Previano Koentjoro](mailto:reinhart_previano@yahoo.com) | glab-pipeline: add page (#7642) | 2022-01-16T17:58:46 | [41711421a9b3](https://github.com/tldr-pages/tldr/commit/41711421a9b3a3ca9b94d79655ed4a7e8969633d)

