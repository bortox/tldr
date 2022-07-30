---
author: ['bl-ue', 'Flex Zhong', 'marchersimon']
date: 1630394029
title: "powershell"
description: "powershell, 专为系统管理而设计的命令行 shell 和脚本语言。"
categories: "windows"
---
> 更多信息：<https://docs.microsoft.com/windows-server/administration/windows-commands/powershell>.

- 在命令提示符窗口中启动 Windows PowerShell 会话：

```bash
powershell
```

- 加载一个特定的 PowerShell 控制台文件：

```bash
powershell -PSConsoleFile 路径/file
```

- 用指定版本的 PowerShell 启动会话：

```bash
powershell -Version 版本
```

- 防止运行启动命令后 shell 退出：

```bash
powershell -NoExit
```

- 描述发送到 PowerShell 的数据格式：

```bash
powershell -InputFormat Text|XML
```

- 设定 PowerShell 输出的格式：

```bash
powershell -OutputFormat Text|XML
```

- 显示帮助：

```bash
powershell -Help
```
对该文件所做的修改清单


作者 | 描述 | ISO 8601日期格式 | 链接到GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | Chinese pages: remove space in More info link (#6305) | 2021-08-31T09:13:49 | [c70c0c26884e](https://github.com/tldr-pages/tldr/commit/c70c0c26884ee74fabb640cd842d1e4c72d9df4b)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | Chinese pages: correct Chinese punctuation (#5240) | 2021-08-02T10:41:09 | [289e30dfb3d1](https://github.com/tldr-pages/tldr/commit/289e30dfb3d1d73bade9e3610e12bfc90e9270ae)
[Flex Zhong](mailto:chungzh07@gmail.com) | matlab, powershell: add Chinese translation (#4743) | 2020-10-19T19:17:12 | [e46977260b3a](https://github.com/tldr-pages/tldr/commit/e46977260b3a9214ff57335aec496fc58b96aed2)

