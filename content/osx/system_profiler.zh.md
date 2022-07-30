---
author: ['wizarot', 'bl-ue', 'meowmeowcat']
date: 1636919159
title: "system_profiler"
description: "system_profiler, 报告系统硬件和软件配置。"
categories: "osx"
---
> 更多信息：<https://ss64.com/osx/system_profiler.html>.

- 显示可由 System Profiler.app 打开的完整系统资源报告：

```bash
system_profiler -xml > MyReport.spx
```

- 显示硬件概述（型号、CPU、内存、串行等）：

```bash
system_profiler SPHardwareDataType
```

- 打印系统序列号：

```bash
system_profiler SPHardwareDataType|grep "Serial Number (system)" |awk '{print $4}'
```
对该文件所做的修改清单


作者 | 描述 | ISO 8601日期格式 | 链接到GitHub
------|-----|-----|-----
[meowmeowcat](mailto:meowmeowcat1211@gmail.com) | osx/s*: add link (#7428) | 2021-11-14T20:45:59 | [a36f8550d81b](https://github.com/tldr-pages/tldr/commit/a36f8550d81be6fbe04cb43f3d0a34f30e024b86)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | Chinese pages: correct Chinese punctuation (#5240) | 2021-08-02T10:41:09 | [289e30dfb3d1](https://github.com/tldr-pages/tldr/commit/289e30dfb3d1d73bade9e3610e12bfc90e9270ae)
[wizarot](mailto:wizarot@qq.com) | system_profiler: add Chinese translation | 2019-03-15T12:47:29 | [75271679b61a](https://github.com/tldr-pages/tldr/commit/75271679b61a6444e4763a1f5bd772d09c09574d)

