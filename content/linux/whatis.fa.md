---
author: ['Taymaz Esmaeli', 'bl-ue', 'marchersimon']
date: 1659075216
title: "whatis, TLDR Pages"
description: "whatis, نمایش توضیحات یک خطی از صفحات راهنما."
categories: "linux"
---
> اطلاعات بیشتر: <https://manned.org/whatis>.

- نمایش توضیحات یک دستور از صفحات راهنما:

```bash
whatis command
```

- توضیحات در آخر خط ترمینال برش نمی خورد:

```bash
whatis --long command
```

- نمایش توضیحات تمامی دستورات مطابق با الگو:

```bash
whatis --wildcard net*
```

- جستجو در توضیحات صفحات راهنما با عبارات منظم:

```bash
whatis --regex 'wish[0-9]\.[0-9]'
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | Sync more information links with all translations (#8256) | 2022-07-29T08:13:36 | [1f610a952ea0](https://github.com/tldr-pages/tldr/commit/1f610a952ea0d53e0a1bdbd1246ef81f24db2f3f)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | *: trim multiple spaces, fix line endings | 2021-04-04T01:44:24 | [04dd546e2de7](https://github.com/tldr-pages/tldr/commit/04dd546e2de7f59f40a867acca6f46b0dc8ea9b4)
[Taymaz Esmaeli](mailto:56496286+opoet7@users.noreply.github.com) | yum, whereis, whatis: add Persian translation (#5459) | 2021-03-16T15:55:04 | [1297618062b2](https://github.com/tldr-pages/tldr/commit/1297618062b2e998ebcf4f84d290cf6033e3048f)

