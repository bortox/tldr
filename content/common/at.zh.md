---
author: ['Mercurio', 'lincc', 'marchersimon']
date: 1659075216
title: "at"
description: "at, 在一段时间后，执行单次命令。"
categories: "common"
---
> atd 服务（或 atrun）需要处于运行状态，以保证命令成功执行。

> 更多信息：<https://manned.org/at>.

- 5 分钟后，执行标准输入中的命令（命令输入完成后按 `Ctrl + D`）：

```bash
at now + 5 minutes
```

- 在今天上午 10:00 执行标准输入中的命令：

```bash
echo "./make_db_backup.sh" | at 1000
```

- 下周二晚上 9:30 执行指定文件中包含的命令：

```bash
at -f path/to/file 9:30 PM Tue
```
对该文件所做的修改清单


作者 | 描述 | ISO 8601日期格式 | 链接到GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | Sync more information links with all translations (#8256) | 2022-07-29T08:13:36 | [1f610a952ea0](https://github.com/tldr-pages/tldr/commit/1f610a952ea0d53e0a1bdbd1246ef81f24db2f3f)
[lincc](mailto:46962923+blueskyson@users.noreply.github.com) | *: update links via set-more-info-link.py (#7611) | 2022-01-29T21:17:39 | [b99f3da787c6](https://github.com/tldr-pages/tldr/commit/b99f3da787c6f43a545b9cb5ebd8265b1367fbc4)
[Mercurio](mailto:32540679+SignorMercurio@users.noreply.github.com) | at: add Chinese translation (#6903) | 2021-10-10T16:14:46 | [b310f9e385b2](https://github.com/tldr-pages/tldr/commit/b310f9e385b2ccd6ff6b81a2380443c9301da36f)

