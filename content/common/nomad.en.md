---
author: ['Starbeamrainbowlabs']
date: 1587982639
title: "nomad, TLDR Pages"
description: "nomad, Distributed, highly available, datacenter-aware scheduler."
categories: "common"
---
> More information: <https://www.nomadproject.io/docs/commands/>.

- Show the status of nodes in the cluster:

```bash
nomad node status
```

- Validate a job file:

```bash
nomad job validate path/to/file.nomad
```

- Plan a job for execution on the cluster:

```bash
nomad job plan path/to/file.nomad
```

- Run a job on the cluster:

```bash
nomad job run path/to/file.nomad
```

- Show the status of jobs currently running on the cluster:

```bash
nomad job status
```

- Show the detailed status information about a specific job:

```bash
nomad job status job_name
```

- Follow the logs of a specific allocation:

```bash
nomad alloc logs alloc_id
```

- Show the status of storage volumes:

```bash
nomad volume status
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Starbeamrainbowlabs](mailto:sbrl@starbeamrainbowlabs.com) | nomad: add page (#4008) | 2020-04-27T12:17:19 | [35b643410fdf](https://github.com/tldr-pages/tldr/commit/35b643410fdfc09573dd22b5801ff5434129b789)

