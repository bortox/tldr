---
author: ['David Zhang', 'lincc']
date: 1643487459
title: "sacctmgr"
description: "sacctmgr, 查看、配置、管理 Slurm 账户。"
categories: "linux"
---
> 更多信息：<https://slurm.schedmd.com/sacctmgr.html>.

- 显示现有配置：

```bash
sacctmgr show configuration
```

- 向 Slurm 数据库添加集群：

```bash
sacctmgr add cluster 集群名
```

- 向 Slurm 数据库添加账户：

```bash
sacctmgr add account 账户名 cluster=账户所在集群
```

- 以指定格式显示用户、账户资源关联、集群、账户的详细信息：

```bash
sacctmgr show user|association|cluster|account format="Accout%10" format="GrpTRES%30"
```
对该文件所做的修改清单


作者 | 描述 | ISO 8601日期格式 | 链接到GitHub
------|-----|-----|-----
[lincc](mailto:46962923+blueskyson@users.noreply.github.com) | *: update links via set-more-info-link.py (#7611) | 2022-01-29T21:17:39 | [b99f3da787c6](https://github.com/tldr-pages/tldr/commit/b99f3da787c6f43a545b9cb5ebd8265b1367fbc4)
[David Zhang](mailto:zdy004007@126.com) | sacctmgr: add Chinese translation (#7588) | 2021-12-31T13:22:18 | [dc8f9639c0a8](https://github.com/tldr-pages/tldr/commit/dc8f9639c0a86c02b24a3a79f91ff4f1d63bf05e)

