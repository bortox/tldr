---
author: ['Starccy', 'Ein Verne', 'bl-ue', 'marchersimon']
date: 1633112881
title: "more, TLDR Pages"
description: "more, 分页显示标准输入或文件的输出。"
categories: "windows"
---
> 更多信息：<https://docs.microsoft.com/windows-server/administration/windows-commands/more>.

- 分页显示标准输入的输出：

```bash
echo test | more
```

- 分页显示一个或多个文件的内容：

```bash
more 文件的路径
```

- 将制表符转换为指定的空格数：

```bash
more 文件的路径 /t空格数
```

- 显示内容前先清屏：

```bash
more 文件的路径 /c
```

- 从第 5 行开始显示输出：

```bash
more 文件的路径 +5
```

- 启用扩展交互模式（请参阅使用帮助）：

```bash
more 文件的路径 /e
```

- 显示全部帮助信息：

```bash
more /?
```
对该文件所做的修改清单


作者 | 描述 | ISO 8601日期格式 | 链接到GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: sync more information links in translations (#6537) | 2021-10-01T20:28:01 | [642dbf2e972e](https://github.com/tldr-pages/tldr/commit/642dbf2e972e388fab8c84ba3b4685fb862b6454)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | Chinese pages: correct Chinese punctuation (#5240) | 2021-08-02T10:41:09 | [289e30dfb3d1](https://github.com/tldr-pages/tldr/commit/289e30dfb3d1d73bade9e3610e12bfc90e9270ae)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | *: clean up token syntax delimiters (#5677) | 2021-04-04T02:08:57 | [289787c7e8c1](https://github.com/tldr-pages/tldr/commit/289787c7e8c1177742d23004198253154fe50c3c)
[Ein Verne](mailto:einverne@gmail.com) | format translation: change colon | 2019-11-02T18:47:23 | [30c2bd4c7ca2](https://github.com/tldr-pages/tldr/commit/30c2bd4c7ca2385e09cc00f15ad651e195b82e65)
[Ein Verne](mailto:einverne@gmail.com) | format translation: change period | 2019-11-02T18:47:23 | [f0f2764de273](https://github.com/tldr-pages/tldr/commit/f0f2764de2737f4c7bc75feeec5499117dea6ed0)
[Ein Verne](mailto:einverne@gmail.com) | format zh translations | 2019-11-02T18:47:23 | [7f995941edad](https://github.com/tldr-pages/tldr/commit/7f995941edaddaa6bd3208856ec539f5439f7ef4)
[Starccy](mailto:452276725@qq.com) | more: add Chinese translation | 2019-03-12T12:56:23 | [0bd5c90cce49](https://github.com/tldr-pages/tldr/commit/0bd5c90cce493dff9e7389cc490b73a96aa16b89)

