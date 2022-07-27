---
author: ['Taymaz Esmaeli', 'Dario Vladović', 'bl-ue', 'marchersimon']
date: 1617493464
title: "cp, TLDR Pages"
description: "cp, کپی فایل ها و دایرکتوری ها."
categories: "common"
---
> اطلاعات بیشتر: <https://www.gnu.org/software/coreutils/cp>.

- کپی فایل از مبدا به مقصد مشخص شده:

```bash
cp path/to/source_file.ext path/to/target_file.ext
```

- کپی فایل به دایرکتوری مشخص شده با حفظ نام فایل:

```bash
cp path/to/source_file.ext path/to/target_parent_directory
```

- کپی یک دایرکتوری به صورت کامل به مقصد جدید(اگر در مقصد دایرکتوری وجود داشت دایرکتوری مبدا در داخل دایرکتوری مقصد کپی می شود):

```bash
cp -R path/to/source_directory path/to/target_directory
```

- کپی یک دایرکتوری به صورت کامل با نمایش جزییات (نمایش فایل های کپی شده):

```bash
cp -vR path/to/source_directory path/to/target_directory
```

- کپی کلیه فایل های با پسوند `txt` به دایرکتوری مقصد در حالت تعاملی (قبل از بازنویسی تاییده توسط کاربر نیاز است):

```bash
cp -i *.txt path/to/target_directory
```

- کپی لینک به مقصد بدون ارجاع به فایل اصلی:

```bash
cp -L link path/to/target_directory
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | *: trim multiple spaces, fix line endings | 2021-04-04T01:44:24 | [04dd546e2de7](https://github.com/tldr-pages/tldr/commit/04dd546e2de7f59f40a867acca6f46b0dc8ea9b4)
[Dario Vladović](mailto:d.vladimyr@gmail.com) | coreutils*: use short more info links (#5658) | 2021-04-01T17:54:26 | [4830093903f6](https://github.com/tldr-pages/tldr/commit/4830093903f66ccf3ebbc2ecf477286e45edac59)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | cp: add more information link (#5556) | 2021-03-30T12:30:03 | [ad46ebe87a57](https://github.com/tldr-pages/tldr/commit/ad46ebe87a578bcb5e61d26addcf1bdfe287d75f)
[Taymaz Esmaeli](mailto:56496286+opoet777@users.noreply.github.com) | cp: fix Persian translation (#5192) | 2021-01-28T11:02:30 | [de1bb7bd0040](https://github.com/tldr-pages/tldr/commit/de1bb7bd004053cd2737f2ae71feaf3c9853fbde)
[Taymaz Esmaeli](mailto:56496286+opoet777@users.noreply.github.com) | cp: add Persian translation (#5189) | 2021-01-26T19:28:52 | [4b1a8245ed96](https://github.com/tldr-pages/tldr/commit/4b1a8245ed968c3464ff6f12c5722aed7fca347b)

