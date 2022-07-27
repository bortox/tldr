---
author: ['Gary Li', 'bl-ue', 'marchersimon']
date: 1633112881
title: "afinfo, TLDR Pages"
description: "afinfo, 显示音频文件元数据（Metadata）详细信息（OS X）。"
categories: "osx"
---
> OS X 自带命令。

> 更多信息：<https://ss64.com/osx/afinfo.html>.

- 显示给定音频文件的详细信息：

```bash
afinfo 目标 / 路径 / 文件
```

- 显示简化的音频文件信息（单行）：

```bash
afinfo -b 目标 / 路径 / 文件
```

- 显示音频文件的元数据信息以及其 InfoDictionary 词典：

```bash
afinfo -i 目标 / 路径 / 文件
```

- 以 xml 格式显示音频文件信息：

```bash
afinfo -x 目标 / 路径 / 文件
```

- 显示警告信息（如存在）：

```bash
afinfo --warnings 目标 / 路径 / 文件
```

- 显示完整用法帮助：

```bash
afinfo -h
```
对该文件所做的修改清单


作者 | 描述 | ISO 8601日期格式 | 链接到GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: sync more information links in translations (#6537) | 2021-10-01T20:28:01 | [642dbf2e972e](https://github.com/tldr-pages/tldr/commit/642dbf2e972e388fab8c84ba3b4685fb862b6454)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | Chinese pages: correct Chinese punctuation (#5240) | 2021-08-02T10:41:09 | [289e30dfb3d1](https://github.com/tldr-pages/tldr/commit/289e30dfb3d1d73bade9e3610e12bfc90e9270ae)
[Gary Li](mailto:15998246+garily@users.noreply.github.com) | afinfo: add page (en, zh) (#3652) | 2019-12-10T11:29:33 | [8df38c39895c](https://github.com/tldr-pages/tldr/commit/8df38c39895ce6c6bf6e1b112568083adb14ea61)

