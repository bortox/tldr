---
author: ['zhouquan', 'Seth Falco', 'marchersimon', 'bl-ue']
date: 1648358715
title: "act, TLDR Pages"
description: "act, 使用 Docker 本地运行 GitHub Actions."
categories: "common"
---
> 更多信息：<https://github.com/nektos/act>.

- 列出可用的 actions 清单：

```bash
act -l
```

- 运行默认 event：

```bash
act
```

- 运行指定 event：

```bash
act 事件类型
```

- 运行指定 action：

```bash
act -a action_id
```

- 非实际运行 actions（也就是 dry-run 模式）：

```bash
act -n
```

- 展示详细记录：

```bash
act -v
```
对该文件所做的修改清单


作者 | 描述 | ISO 8601日期格式 | 链接到GitHub
------|-----|-----|-----
[Seth Falco](mailto:seth@falco.fun) | *: normalize colons (#7913) | 2022-03-27T07:25:15 | [27ff55fc2eea](https://github.com/tldr-pages/tldr/commit/27ff55fc2eea445eb5216c3b1d934960539fc024)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | Chinese pages: remove space in More info link (#6305) | 2021-08-31T09:13:49 | [c70c0c26884e](https://github.com/tldr-pages/tldr/commit/c70c0c26884ee74fabb640cd842d1e4c72d9df4b)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | Chinese pages: correct Chinese punctuation (#5240) | 2021-08-02T10:41:09 | [289e30dfb3d1](https://github.com/tldr-pages/tldr/commit/289e30dfb3d1d73bade9e3610e12bfc90e9270ae)
[zhouquan](mailto:748583403@qq.com) | aapt to buku: add Chinese translation (#4846) | 2020-11-04T21:12:56 | [8f73cca2e7aa](https://github.com/tldr-pages/tldr/commit/8f73cca2e7aac9b8ef6d721d2083d64ed9879d1c)

