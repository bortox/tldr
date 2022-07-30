---
author: ['bl-ue', 'Flex Zhong', 'marchersimon']
date: 1630394029
title: "logsave"
description: "logsave, 将一个命令的输出保存在日志文件中。"
categories: "linux"
---
> 更多信息：<https://manned.org/logsave>.

- 使用指定的参数执行命令并将其输出保存到日志文件中：

```bash
logsave path/to/logfile command
```

- 从标准输入中获取输入并将其保存在日志文件中：

```bash
logsave logfile -
```

- 将输出追加到日志文件，而不是替换其当前内容：

```bash
logsave -a logfile command
```

- 显示详细输出：

```bash
logsave -v logfile command
```
对该文件所做的修改清单


作者 | 描述 | ISO 8601日期格式 | 链接到GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | Chinese pages: remove space in More info link (#6305) | 2021-08-31T09:13:49 | [c70c0c26884e](https://github.com/tldr-pages/tldr/commit/c70c0c26884ee74fabb640cd842d1e4c72d9df4b)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | Chinese pages: correct Chinese punctuation (#5240) | 2021-08-02T10:41:09 | [289e30dfb3d1](https://github.com/tldr-pages/tldr/commit/289e30dfb3d1d73bade9e3610e12bfc90e9270ae)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | multiple pages: replace all die.net links (#5528) Most of the links were replaced by manned.org, except when there are more up-to-date [...] | 2021-04-16T16:42:14 | [dac4a710772f](https://github.com/tldr-pages/tldr/commit/dac4a710772f9adef5b9883172fb30ed2416c0eb)
[Flex Zhong](mailto:chungzh07@gmail.com) | logsave, winget: add Chinese translation (#4517) | 2020-10-06T18:05:51 | [350d9bd3f751](https://github.com/tldr-pages/tldr/commit/350d9bd3f7510c8de53a61aa30daa42ed6d53319)

