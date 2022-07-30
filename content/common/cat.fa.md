---
author: ['Dario Vladović', 'bl-ue', 'Taymaz Esmaeli', 'marchersimon']
date: 1617493464
title: "cat"
description: "cat, چاپ و ترکیب کردن فایل ها."
categories: "common"
---
> اطلاعات بیشتر: <https://www.gnu.org/software/coreutils/cat>.

- چاپ محتویات فایل بر روی صفحه نمایش:

```bash
cat file
```

- ادغام چند فایل با هم و ایجاد فایل جدید:

```bash
cat file1 file2 > target_file
```

- ادغام چند فایل با هم و اضافه کردن آن به فایل مقصد:

```bash
cat file1 file2 >> target_file
```

- شمارش تعداد خط های فایل:

```bash
cat -n file
```

- نمایش محتویات فایل بدون فضای خالی (نا مناسب برای چاپ):

```bash
cat -v -t -e file
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | *: trim multiple spaces, fix line endings | 2021-04-04T01:44:24 | [04dd546e2de7](https://github.com/tldr-pages/tldr/commit/04dd546e2de7f59f40a867acca6f46b0dc8ea9b4)
[Dario Vladović](mailto:d.vladimyr@gmail.com) | coreutils*: use short more info links (#5658) | 2021-04-01T17:54:26 | [4830093903f6](https://github.com/tldr-pages/tldr/commit/4830093903f66ccf3ebbc2ecf477286e45edac59)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | cat: change more information link (#5551) | 2021-03-30T12:31:55 | [3d97ba7785c1](https://github.com/tldr-pages/tldr/commit/3d97ba7785c175e55c9c9ac06f1f20b08837ea5d)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | multiple pages: trim trailing whitespace (#5213) | 2021-01-31T22:16:00 | [d679ad10161d](https://github.com/tldr-pages/tldr/commit/d679ad10161dd1fe7e0dd2a62358869df2a32080)
[Taymaz Esmaeli](mailto:56496286+opoet777@users.noreply.github.com) | cat, ver: add Persian translation (#5181) | 2021-01-25T14:27:02 | [fd1c2ec42574](https://github.com/tldr-pages/tldr/commit/fd1c2ec425744ec02d7536a826b06c5fba910307)

