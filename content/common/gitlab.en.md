---
author: ['Pierre Rudloff', 'marchersimon']
date: 1631521281
title: "gitlab"
description: "gitlab, Ruby wrapper and CLI for the GitLab API."
categories: "common"
---
> Some subcommands such as `gitlab ctl` have their own usage documentation.

> More information: <https://narkoz.github.io/gitlab/>.

- Create a new project:

```bash
gitlab create_project project_name
```

- Get info about a specific commit:

```bash
gitlab commit project_name commit_hash
```

- Get info about jobs in a CI pipeline:

```bash
gitlab pipeline_jobs project_name pipeline_id
```

- Start a specific CI job:

```bash
gitlab job_play project_name job_id
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | mention subcommands in every base page (#6383) | 2021-09-13T10:21:21 | [bd677b8b4826](https://github.com/tldr-pages/tldr/commit/bd677b8b48260e301fb99fea794f4dc1458d1562)
[Pierre Rudloff](mailto:50333926+prudloff-insite@users.noreply.github.com) | gitlab: add page (#3571) | 2019-11-16T07:21:48 | [cee841001075](https://github.com/tldr-pages/tldr/commit/cee84100107520ff3b41ed398c6b08924f5ae640)

