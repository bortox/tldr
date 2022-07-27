---
author: ['Stig124', '千玄子', 'marchersimon']
date: 1630394029
title: "addr2line, TLDR Pages"
description: "addr2line, 将二进制文件地址转换成文件名和行数。"
categories: "linux"
---
> 更多信息：<https://manned.org/addr2line>.

- 显示可执行文件的指令地址对应源代码的文件名和行数：

```bash
addr2line --exe=可执行文件路径 地址
```

- 显示函数名、文件名和行数：

```bash
addr2line --exe=可执行文件路径 --functions 地址
```

- 将 C++ 代码函数名符号重组：

```bash
addr2line --exe=可执行文件地址 --functions --demangle 地址
```
对该文件所做的修改清单


作者 | 描述 | ISO 8601日期格式 | 链接到GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | Chinese pages: remove space in More info link (#6305) | 2021-08-31T09:13:49 | [c70c0c26884e](https://github.com/tldr-pages/tldr/commit/c70c0c26884ee74fabb640cd842d1e4c72d9df4b)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: replace `java` with `Java` and `c++` with `C++` (#6224) | 2021-07-13T10:59:48 | [b615ea1e3495](https://github.com/tldr-pages/tldr/commit/b615ea1e34951c855e72470b73522ed0e0963d87)
[Stig124](mailto:stigpro@outlook.fr) | linux/[a-g]: add more information link (#6076) | 2021-07-09T16:45:55 | [3697c62b5e5c](https://github.com/tldr-pages/tldr/commit/3697c62b5e5cd9bae7a99c591cb81d1ddcfbf792)
[千玄子](mailto:ownbyzjuyk@gmail.com) | a2dismod to avahi-browse: add Chinese translation (#5246) | 2021-05-01T20:43:23 | [92f09753c6de](https://github.com/tldr-pages/tldr/commit/92f09753c6de9ab7cc8df9cd8d194f824252dd23)

