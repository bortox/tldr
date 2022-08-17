---
author: ['LiLittleCat']
date: 1660627854
title: "find"
description: "find, 在指定目录树下递归查找文件或目录。"
categories: "common"
---
> 更多信息：<https://manned.org/find>.

- 通过扩展名查找文件：

```bash
find 指定目录 -name '*.ext'
```

- 查找匹配多个路径或名称模式的文件：

```bash
find 指定目录 -path '**/path/**/*.ext' -or -name '*pattern*'
```

- 查找匹配指定名称的目录，不区分大小写：

```bash
find 指定目录 -type d -iname '*lib*'
```

- 查找匹配指定模式的文件，排除特定路径：

```bash
find 指定目录 -name '*.py' -not -path '*/site-packages/*'
```

- 查找符合指定大小范围的文件：

```bash
find 指定目录 -size +500k -size -10M
```

- 对每个文件运行命令（在命令中使用 `{}` 代表当前文件）：

```bash
find 指定目录 -name '*.ext' -exec wc -l {} \;
```

- 查找最近 7 天修改的文件并删除：

```bash
find 指定目录 -daystart -mtime -7 -delete
```

- 查找空（0 字节）的文件并删除：

```bash
find 指定目录 -type f -empty -delete
```
对该文件所做的修改清单


作者 | 描述 | ISO 8601日期格式 | 链接到GitHub
------|-----|-----|-----
[LiLittleCat](mailto:luoyukongchan@outlook.com) | find: add Chinese translation (#8358) | 2022-08-16T07:30:54 | [58b46d5a2804](https://github.com/tldr-pages/tldr/commit/58b46d5a280433d17026a1dc1549b82483e1ddbc)

