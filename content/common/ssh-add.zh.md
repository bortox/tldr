---
author: ['syleung', 'marchersimon']
date: 1633351190
title: "ssh-add"
description: "ssh-add, 在 ssh 代理中管理加载的 ssh 密钥。"
categories: "common"
---
> 需要确保 ssh 代理已启动并正在运行以加载其中的密钥。

> 更多信息：<https://man.openbsd.org/ssh-add>.

- 将 `~/.ssh` 中的默认 ssh 密钥添加到 `ssh` 代理：

```bash
ssh-add
```

- 向 ssh 代理添加指定密钥：

```bash
ssh-add 目录 / 私钥文件
```

- 列出当前加载的密钥的指纹：

```bash
ssh-add -l
```

- 从 ssh 代理中删除密钥：

```bash
ssh-add -d 目录 / 私钥文件
```

- 从 ssh 代理中删除所有当前已有的密钥：

```bash
ssh-add -D
```

- 向 ssh 代理和密钥链添加密钥：

```bash
ssh-add -K 目录 / 私钥文件
```
对该文件所做的修改清单


作者 | 描述 | ISO 8601日期格式 | 链接到GitHub
------|-----|-----|-----
[syleung](mailto:syleung@users.noreply.github.com) | common/ssh*: add more information link (#6659) | 2021-10-04T14:39:50 | [a092be52d7de](https://github.com/tldr-pages/tldr/commit/a092be52d7ded26ec56154160c90900c6338e76d)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | feh, hostname, fc, ssh-add: move to common (#6487) | 2021-09-08T08:55:55 | [4ef097c3581a](https://github.com/tldr-pages/tldr/commit/4ef097c3581a5a5d6a740b23629e82852b59680c)

