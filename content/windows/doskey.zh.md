---
author: ['Starccy', 'Ein Verne', 'bl-ue', 'marchersimon']
date: 1633112881
title: "doskey, TLDR Pages"
description: "doskey, 管理宏，Windows 命令和命令行。"
categories: "windows"
---
> 更多信息：<https://docs.microsoft.com/windows-server/administration/windows-commands/doskey>.

- 列出可用的宏：

```bash
doskey /macros
```

- 创建一个新的宏：

```bash
doskey 宏的名称 = "命令"
```

- 为指定可执行文件创建新的宏：

```bash
doskey /exename=可执行文件名 宏的名称 = "命令"
```

- 删除一个宏：

```bash
doskey 宏的名称 =
```

- 列出所有储存在内存中的命令：

```bash
doskey /history
```

- 将宏保存到文件以便于移植：

```bash
doskey /macros > 保存宏的文件名
```

- 从文件中加载宏：

```bash
doskey /macrofile = 保存宏的文件名
```
对该文件所做的修改清单


作者 | 描述 | ISO 8601日期格式 | 链接到GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: sync more information links in translations (#6537) | 2021-10-01T20:28:01 | [642dbf2e972e](https://github.com/tldr-pages/tldr/commit/642dbf2e972e388fab8c84ba3b4685fb862b6454)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | Chinese pages: correct Chinese punctuation (#5240) | 2021-08-02T10:41:09 | [289e30dfb3d1](https://github.com/tldr-pages/tldr/commit/289e30dfb3d1d73bade9e3610e12bfc90e9270ae)
[Ein Verne](mailto:einverne@gmail.com) | format translation: change colon | 2019-11-02T18:47:23 | [30c2bd4c7ca2](https://github.com/tldr-pages/tldr/commit/30c2bd4c7ca2385e09cc00f15ad651e195b82e65)
[Ein Verne](mailto:einverne@gmail.com) | format translation: change period | 2019-11-02T18:47:23 | [f0f2764de273](https://github.com/tldr-pages/tldr/commit/f0f2764de2737f4c7bc75feeec5499117dea6ed0)
[Ein Verne](mailto:einverne@gmail.com) | format zh translations | 2019-11-02T18:47:23 | [7f995941edad](https://github.com/tldr-pages/tldr/commit/7f995941edaddaa6bd3208856ec539f5439f7ef4)
[Starccy](mailto:452276725@qq.com) | doskey: add Chinese translation | 2019-03-12T12:56:23 | [dadbd487a41c](https://github.com/tldr-pages/tldr/commit/dadbd487a41c5d51be02a4670fd587583d24541e)

