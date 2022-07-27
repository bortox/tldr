---
author: ['Taymaz Esmaeli', 'Joe Nichols', 'bl-ue']
date: 1643127154
title: "yum, TLDR Pages"
description: "yum, ابزار مدیریت بسته برای ردهت، فدورا و سنت اواس(برای نسخه های قدیمی)."
categories: "linux"
---
> اطلاعات بیشتر: <https://manned.org/yum>.

- نصب یک بسته:

```bash
yum install package
```

- نصب یک بسته با فرض بر اینکه پاسخ شما برای تمامی سوالات بله است(با گزینه update هم می توان از این روش استفاده کرد، مناسب برای به روز رسانی خودکار):

```bash
yum -y install package
```

- پیدا کردن بسته ای که دستور مورد نظر را فراهم می کند:

```bash
yum provides command
```

- حذف یک بسته:

```bash
yum remove package
```

- نمایش به روز رسانی ها برای بسته های نصب شده:

```bash
yum check-update
```

- به روز رسانی بسته های نصب شده به آخرین نسخه موجود:

```bash
yum upgrade
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Joe Nichols](mailto:GhostViz@users.noreply.github.com) | yum: use manned for more information link (#7708) | 2022-01-25T17:12:34 | [92343a1f94ac](https://github.com/tldr-pages/tldr/commit/92343a1f94ac280873c24487b3300bdd584039df)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | *: trim multiple spaces, fix line endings | 2021-04-04T01:44:24 | [04dd546e2de7](https://github.com/tldr-pages/tldr/commit/04dd546e2de7f59f40a867acca6f46b0dc8ea9b4)
[Taymaz Esmaeli](mailto:56496286+opoet7@users.noreply.github.com) | yum, whereis, whatis: add Persian translation (#5459) | 2021-03-16T15:55:04 | [1297618062b2](https://github.com/tldr-pages/tldr/commit/1297618062b2e998ebcf4f84d290cf6033e3048f)

