---
author: ['Giorgio Lasala']
date: 1636010366
title: "az pipelines, TLDR Pages"
description: "az pipelines, Manage Azure Pipelines resources."
categories: "common"
---
> Part of `azure-cli`.

> More information: <https://docs.microsoft.com/cli/azure/pipelines>.

- Create a new Azure Pipeline (YAML based):

```bash
az pipelines create --org organization_url --project project_name --name pipeline_name --description description --repository repository_name --branch branch_name
```

- Delete a specific pipeline:

```bash
az pipelines delete --org organization_url --project project_name --id pipeline_id
```

- List pipelines:

```bash
az pipelines list --org organization_url --project project_name
```

- Enqueue a specific pipeline to run:

```bash
az pipelines run --org organization_url --project project_name --name pipeline_name
```

- Get the details of a specific pipeline:

```bash
az pipelines show --org organization_url --project project_name --name pipeline_name
```

- Update a specific pipeline:

```bash
az pipelines update --org organization_url --project project_name --name pipeline_name --new-name pipeline_new_name --new-folder-path user1/production_pipelines
```

- Get a list of agents in a pool:

```bash
az pipelines agent list --org organization_url --pool-id agent_pool
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Giorgio Lasala](mailto:salem84@users.noreply.github.com) | az-pipelines: add page (#7186) | 2021-11-04T08:19:26 | [833872c8e980](https://github.com/tldr-pages/tldr/commit/833872c8e9802c144aaf97e52181b3a4ed63396e)

