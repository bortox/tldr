---
author: ['Ivan Aracki']
date: 1561990118
title: "velero, TLDR Pages"
description: "velero, Backup and migrate Kubernetes applications and their persistent volumes."
categories: "common"
---
> More information: <https://github.com/heptio/velero>.

- Create a backup containing all resources:

```bash
velero backup create backup_name
```

- List all backups:

```bash
velero backup get
```

- Delete a backup:

```bash
velero backup delete backup_name
```

- Create a weekly backup, each living for 90 days (2160 hours):

```bash
velero schedule create schedule_name --schedules="@every 7d" --ttl 2160h0m0s
```

- Create a restore from the latest successful backup triggered by specific schedule:

```bash
velero restore create --from-schedule schedule_name
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Ivan Aracki](mailto:aracki.ivan@gmail.com) | velero: add page (#3153) | 2019-07-01T16:08:38 | [556b410c8b3d](https://github.com/tldr-pages/tldr/commit/556b410c8b3d2f1cb6e48fddf1262308b7fb6404)

