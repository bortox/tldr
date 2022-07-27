---
author: ['Nikhil Reddy', 'CleanMachine1', 'David Zhang']
date: 1657497901
title: "sacctmgr, TLDR Pages"
description: "sacctmgr, View, setup, and manage Slurm accounts."
categories: "linux"
---
> More information: <https://slurm.schedmd.com/sacctmgr.html>.

- Show current configuration:

```bash
sacctmgr show configuration
```

- Add a cluster to the slurm database:

```bash
sacctmgr add cluster cluster_name
```

- Add an account to the slurm database:

```bash
sacctmgr add account account_name cluster=cluster_of_account
```

- Show details of user/association/cluster/account using a specific format:

```bash
sacctmgr show user|association|cluster|account format="Account%10" format="GrpTRES%30"
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[CleanMachine1](mailto:78213164+CleanMachine1@users.noreply.github.com) | linux/*: fix spelling errors | 2022-07-11T02:05:01 | [42bb014b2f6e](https://github.com/tldr-pages/tldr/commit/42bb014b2f6eab426e6225c75a2ec49105813983)
[CleanMachine1](mailto:78213164+CleanMachine1@users.noreply.github.com) | *: fix spelling mistakes (#8072) | 2022-05-04T19:12:15 | [c2a5c8603386](https://github.com/tldr-pages/tldr/commit/c2a5c8603386f1720b996b839802fae1fb60ba8a)
[David Zhang](mailto:zdy004007@126.com) | sacctmgr: add Chinese translation (#7588) | 2021-12-31T13:22:18 | [dc8f9639c0a8](https://github.com/tldr-pages/tldr/commit/dc8f9639c0a86c02b24a3a79f91ff4f1d63bf05e)
[Nikhil Reddy](mailto:35285981+npalladium@users.noreply.github.com) | sacctmgr, sreport: add page (#4646) | 2020-10-15T00:16:46 | [6d0b062c3624](https://github.com/tldr-pages/tldr/commit/6d0b062c3624d0ca0fe3eb071bdaf26f4b41cfc4)

