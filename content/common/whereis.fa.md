---
author: ['derNiklaas', 'marchersimon']
date: 1633404950
title: "whereis"
description: "whereis, پیداکردن فایل اجرایی، سورس، صفحه راهنما برای یک دستور."
categories: "common"
---
> اطلاعات بیشتر: <https://manned.org/whereis>.

- پیداکردن فایل اجرایی، سورس و صفحه راهنما برای ssh:

```bash
whereis ssh
```

- پیداکردن فایل اجرایی و صفحه راهنما برای ls:

```bash
whereis -bm ls
```

- پیداکردن سورس برای gcc و صفحه راهنما برای git:

```bash
whereis -s gcc -m git
```

- پیداکردن فایل اجرایی برای gcc در مسیر `/usr/bin/`:

```bash
whereis -b -B /usr/bin/ -f gcc
```

- پیدا کردن فایل های اجرایی غیر عادی(برای آنهایی که بیشتر از یک فایل اجرایی در سیستم دارند):

```bash
whereis -u *
```

- پیدا کردن صفحات راهنمای غیر عادی(برای آنهایی که بیشتر از یک فایل اجرایی در سیستم دارند):

```bash
whereis -u -m *
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[derNiklaas](mailto:derNiklaas@users.noreply.github.com) | wall, watch, whereis, whiptail, wipefs, wmctrl, wodim: add link (#6784) | 2021-10-05T05:35:50 | [e0442c6f98f5](https://github.com/tldr-pages/tldr/commit/e0442c6f98f5e01ffc3acd1398249cf0a8a3673d)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | whereis, xar, yank: move to common (#6552) | 2021-09-19T02:59:20 | [e94e6af88289](https://github.com/tldr-pages/tldr/commit/e94e6af88289f26bf25c85b45971f240f56d8672)

