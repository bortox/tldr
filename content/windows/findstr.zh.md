---
author: ['Starccy', 'Ein Verne', 'bl-ue', 'marchersimon']
date: 1633112881
title: "findstr, TLDR Pages"
description: "findstr, 在一个或多个文件中查找指定的文本。"
categories: "windows"
---
> 更多信息：<https://docs.microsoft.com/windows-server/administration/windows-commands/findstr>.

- 在所有文件中查找以空格分隔的字符串：

```bash
findstr "查询语句 查询语句 .." *
```

- 以递归方式在所有文件中查找以空格分隔的字符串：

```bash
findstr /s "查询语句 查询语句 .." *
```

- 查找时不区分大小写：

```bash
findstr /i "查询语句" *"
```

- 使用正则表达式搜索：

```bash
findstr /r "正则表达式" *
```

- 在所有文本文件中查找文字字符串（包含空格）：

```bash
findstr /c:"查询语句" *.txt
```

- 只查找完全匹配的行：

```bash
findstr /x "查询语句" *
```

- 显示匹配的行的行数：

```bash
findstr /n "查询语句" *
```

- 只显示匹配的文件名：

```bash
findstr /m "查询语句" *
```
对该文件所做的修改清单


作者 | 描述 | ISO 8601日期格式 | 链接到GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: sync more information links in translations (#6537) | 2021-10-01T20:28:01 | [642dbf2e972e](https://github.com/tldr-pages/tldr/commit/642dbf2e972e388fab8c84ba3b4685fb862b6454)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | Chinese pages: correct Chinese punctuation (#5240) | 2021-08-02T10:41:09 | [289e30dfb3d1](https://github.com/tldr-pages/tldr/commit/289e30dfb3d1d73bade9e3610e12bfc90e9270ae)
[Ein Verne](mailto:einverne@gmail.com) | format translation: update | 2019-11-02T18:47:23 | [b33795f8ab11](https://github.com/tldr-pages/tldr/commit/b33795f8ab11d9b0b539e149d5f450af7a059b3a)
[Ein Verne](mailto:einverne@gmail.com) | format translation: change colon | 2019-11-02T18:47:23 | [30c2bd4c7ca2](https://github.com/tldr-pages/tldr/commit/30c2bd4c7ca2385e09cc00f15ad651e195b82e65)
[Ein Verne](mailto:einverne@gmail.com) | format translation: change period | 2019-11-02T18:47:23 | [f0f2764de273](https://github.com/tldr-pages/tldr/commit/f0f2764de2737f4c7bc75feeec5499117dea6ed0)
[Ein Verne](mailto:einverne@gmail.com) | format zh translations | 2019-11-02T18:47:23 | [7f995941edad](https://github.com/tldr-pages/tldr/commit/7f995941edaddaa6bd3208856ec539f5439f7ef4)
[Starccy](mailto:452276725@qq.com) | findstr: add Chinese translation | 2019-03-12T12:56:23 | [378c00b06ccb](https://github.com/tldr-pages/tldr/commit/378c00b06ccbd959ed9ea2065463694dbe363d1c)

