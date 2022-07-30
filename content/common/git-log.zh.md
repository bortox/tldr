---
author: ['Asurada']
date: 1637669239
title: "git log"
description: "git log, 查看提交历史。"
categories: "common"
---
> 更多信息：<https://git-scm.com/docs/git-log>.

- 按时间先后顺序列出当前仓库所有的提交，最近的更新排在最上面：

```bash
git log
```

- 查看指定文件或指定目录的历史，包括每次提交所引入的差异：

```bash
git log -p 路径/到/文件或目录
```

- 显示每次提交的文件修改统计信息：

```bash
git log --stat
```

- 在日志旁以 ASCII 图形显示当前分支提交历史，并只展示提交消息的第一行：

```bash
git log --oneline --graph
```

- 在日志旁以 ASCII 图形显示整个仓库的所有提交、标签、分支：

```bash
git log --oneline --decorate --all --graph
```

- 查看提交消息中包含特定字符串（大小写敏感）的提交：

```bash
git log -i --grep 字符串
```

- 查看特定作者的最近 N 条提交：

```bash
git log -n 数字 --author=作者
```

- 查看两个日期之间的提交（yyyy-mm-dd）：

```bash
git log --before="2017-01-29" --after="2017-01-17"
```
对该文件所做的修改清单


作者 | 描述 | ISO 8601日期格式 | 链接到GitHub
------|-----|-----|-----
[Asurada](mailto:43401755+ousugo@users.noreply.github.com) | git-log: add Chinese translation (#7465) | 2021-11-23T13:07:19 | [dcdc917d1e2a](https://github.com/tldr-pages/tldr/commit/dcdc917d1e2a172aa7bf66f0fd7e1ca4df1e027d)

