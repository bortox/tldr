---
author: ['Taymaz Esmaeli', 'Dario Vladović', 'bl-ue', 'marchersimon']
date: 1617493464
title: "ls, TLDR Pages"
description: "ls, نمایش محتویات دایرکتوری."
categories: "common"
---
> اطلاعات بیشتر: <https://www.gnu.org/software/coreutils/ls>.

- نمایش فایل ها به صورت خطی:

```bash
ls -1
```

- نمایش کلیه فایل ها، شامل فایل های مخفی:

```bash
ls -a
```

- نمایش فایل ها، با این تفاوت که / به نام دایرکتوری ها اضافه می شود:

```bash
ls -F
```

- نمایش فایل ها به همراه مجوزها، مالک، اندازه و تاریخ تغییرات:

```bash
ls -la
```

- نمایش فایل ها به همراه مجوزها، مالک، اندازه و تاریخ تغییرات، اندازه ها به صورت قابل درک برای انسان:

```bash
ls -lh
```

- نمایش فایل ها به همراه مجوزها، مالک، اندازه و تاریخ تغییرات، مرتب شده با اندازه فایل به صورت نزولی:

```bash
ls -lS
```

- نمایش فایل ها به همراه مجوزها، مالک، اندازه و تاریخ تغییرات، مرتب شده با تاریخ تغییر فایل به صورت صعودی:

```bash
ls -ltr
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | *: trim multiple spaces, fix line endings | 2021-04-04T01:44:24 | [04dd546e2de7](https://github.com/tldr-pages/tldr/commit/04dd546e2de7f59f40a867acca6f46b0dc8ea9b4)
[Dario Vladović](mailto:d.vladimyr@gmail.com) | coreutils*: use short more info links (#5658) | 2021-04-01T17:54:26 | [4830093903f6](https://github.com/tldr-pages/tldr/commit/4830093903f66ccf3ebbc2ecf477286e45edac59)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | ls: add link (#5561) | 2021-03-30T09:12:42 | [a0e1beab9bd7](https://github.com/tldr-pages/tldr/commit/a0e1beab9bd704de488fefaca86d0c5e20a7a03b)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | Persian/Farsi pages: fix tldr-lint errors (#5371) | 2021-03-08T20:42:54 | [7e7dfc3bff6c](https://github.com/tldr-pages/tldr/commit/7e7dfc3bff6c41e181e67566064d619672e97fa2)
[Taymaz Esmaeli](mailto:56496286+opoet777@users.noreply.github.com) | ls: remove ی (#5182) | 2021-01-25T13:21:28 | [2624fc0e5919](https://github.com/tldr-pages/tldr/commit/2624fc0e5919abc1251a7bd137a13cb41727ff26)
[Taymaz Esmaeli](mailto:56496286+opoet777@users.noreply.github.com) | ls, cd, tty: add Persian translation (#5159) Co-authored-by: Axel Navarro <navarroaxel@gmail.com> | 2021-01-18T15:30:31 | [3753db1d4703](https://github.com/tldr-pages/tldr/commit/3753db1d4703654bf50c6e642cd16480ac94c804)

