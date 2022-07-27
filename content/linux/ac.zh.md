---
author: ['Stig124', '千玄子', 'marchersimon']
date: 1630394029
title: "ac, TLDR Pages"
description: "ac, 打印用户连接时长数据。"
categories: "linux"
---
> 更多信息：<https://www.gnu.org/software/acct/manual/accounting.html#ac>.

- 以小时为单位打印当前用户连接时间：

```bash
ac
```

- 以小时为单位打印所有用户连接时间：

```bash
ac --individual-totals
```

- 以小时为单位打印特定用户连接时间：

```bash
ac --individual-totals 用户名
```

- 以小时为单位打印特定用户每天连接时间：

```bash
ac --daily-totals --individual-totals 用户名
```

- 显示附加明细：

```bash
ac --compatibility
```
对该文件所做的修改清单


作者 | 描述 | ISO 8601日期格式 | 链接到GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | Chinese pages: remove space in More info link (#6305) | 2021-08-31T09:13:49 | [c70c0c26884e](https://github.com/tldr-pages/tldr/commit/c70c0c26884ee74fabb640cd842d1e4c72d9df4b)
[Stig124](mailto:stigpro@outlook.fr) | linux/[a-g]: add more information link (#6076) | 2021-07-09T16:45:55 | [3697c62b5e5c](https://github.com/tldr-pages/tldr/commit/3697c62b5e5cd9bae7a99c591cb81d1ddcfbf792)
[千玄子](mailto:ownbyzjuyk@gmail.com) | a2dismod to avahi-browse: add Chinese translation (#5246) | 2021-05-01T20:43:23 | [92f09753c6de](https://github.com/tldr-pages/tldr/commit/92f09753c6de9ab7cc8df9cd8d194f824252dd23)

