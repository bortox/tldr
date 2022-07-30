---
author: ['bl-ue', 'marchersimon']
date: 1630394029
title: "runsvdir"
description: "runsvdir, 运行整个目录下的服务。"
categories: "common"
---
> 更多信息：<https://manpages.ubuntu.com/manpages/latest/man8/runsvdir.8.html>.

- 以当前用户身份启动和管理目录中的所有服务：

```bash
runsvdir 目录 / 服务文件
```

- 以 root 用户身份启动和管理目录中的所有服务：

```bash
sudo runsvdir 目录 / 服务文件
```

- 在单独会话中启动服务：

```bash
runsvdir -P 目录 / 服务文件
```
对该文件所做的修改清单


作者 | 描述 | ISO 8601日期格式 | 链接到GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | Chinese pages: remove space in More info link (#6305) | 2021-08-31T09:13:49 | [c70c0c26884e](https://github.com/tldr-pages/tldr/commit/c70c0c26884ee74fabb640cd842d1e4c72d9df4b)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | Chinese pages: correct Chinese punctuation (#5240) | 2021-08-02T10:41:09 | [289e30dfb3d1](https://github.com/tldr-pages/tldr/commit/289e30dfb3d1d73bade9e3610e12bfc90e9270ae)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | runit, runsv, runsvdir, runsvchdir, sv: add more information link and move to common/ (#5648) | 2021-03-31T12:52:31 | [d562842e08a9](https://github.com/tldr-pages/tldr/commit/d562842e08a9fb8d1c71eb165394132acd5d9b3f)

