---
author: ['Nikhil Reddy', 'Seth Falco']
date: 1629050349
title: "sreport, TLDR Pages"
description: "sreport, Generate reports on jobs, users, and clusters from accounting data."
categories: "linux"
---
> More information: <https://slurm.schedmd.com/sreport.html>.

- Show pipe delimited cluster utilization data:

```bash
sreport --parsable cluster utilization
```

- Show number of jobs run:

```bash
sreport job sizes printjobcount
```

- Show users with the highest CPU time use:

```bash
sreport user topuser
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Seth Falco](mailto:seth@falco.fun) | *: fix errors reported by languagetool (#6069) | 2021-08-15T19:59:09 | [3e4c519004a4](https://github.com/tldr-pages/tldr/commit/3e4c519004a471c861cdc609fd7239ee3355671c)
[Nikhil Reddy](mailto:35285981+npalladium@users.noreply.github.com) | sacctmgr, sreport: add page (#4646) | 2020-10-15T00:16:46 | [6d0b062c3624](https://github.com/tldr-pages/tldr/commit/6d0b062c3624d0ca0fe3eb071bdaf26f4b41cfc4)

