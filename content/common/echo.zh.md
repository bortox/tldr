---
author: ['Flex Zhong', 'Dario Vladović', 'Guido Lena Cota', 'bl-ue', 'marchersimon']
date: 1630394029
title: "echo, TLDR Pages"
description: "echo, 输出给定参数。"
categories: "common"
---
> 更多信息：<https://www.gnu.org/software/coreutils/echo>.

- 输出文本信息. 注意： 引号是可选的：

```bash
echo "Hello World"
```

- 输出带有环境变量的信息：

```bash
echo "My path is $PATH"
```

- 打印不带尾随换行符的信息：

```bash
echo -n "Hello World"
```

- 向文件添加信息：

```bash
echo "Hello World" >> file.txt
```

- 启用反斜杠转义的解释（特殊字符）：

```bash
echo -e "Column 1\tColumn 2"
```
对该文件所做的修改清单


作者 | 描述 | ISO 8601日期格式 | 链接到GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | Chinese pages: remove space in More info link (#6305) | 2021-08-31T09:13:49 | [c70c0c26884e](https://github.com/tldr-pages/tldr/commit/c70c0c26884ee74fabb640cd842d1e4c72d9df4b)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | Chinese pages: correct Chinese punctuation (#5240) | 2021-08-02T10:41:09 | [289e30dfb3d1](https://github.com/tldr-pages/tldr/commit/289e30dfb3d1d73bade9e3610e12bfc90e9270ae)
[Dario Vladović](mailto:d.vladimyr@gmail.com) | coreutils*: use short more info links (#5658) | 2021-04-01T17:54:26 | [4830093903f6](https://github.com/tldr-pages/tldr/commit/4830093903f66ccf3ebbc2ecf477286e45edac59)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | echo: add link (#5606) | 2021-03-30T15:54:21 | [206703144d57](https://github.com/tldr-pages/tldr/commit/206703144d576491dbcf66be20770c47ebe329d3)
[Guido Lena Cota](mailto:guido.lenacota@kreuzwerker.de) | Bulk change: move double quotes outside tokens (#4431) | 2020-10-04T19:33:38 | [354d4b8748ee](https://github.com/tldr-pages/tldr/commit/354d4b8748ee58813dd6830ced7c3b11067255d7)
[Flex Zhong](mailto:chungzh07@gmail.com) | ninja, code, cd, echo: add Chinese translations (#4166) | 2020-07-09T22:30:44 | [11ba5e0f0e1b](https://github.com/tldr-pages/tldr/commit/11ba5e0f0e1bcd4ac31a33d3196198d867860b91)

