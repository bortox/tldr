---
author: ['bl-ue', 'Taymaz Esmaeli']
date: 1617493464
title: "alias"
description: "alias, ایجاد نام مستعار -- کلمه ای که جایگزین یک دستور می باشد."
categories: "common"
---
> نام های مستعار طول عمری برابر با جلسه جاری شل مربوطه دارند مگر اینکه در فایل های پیکربندی شل مربوط نظیر `~/.bashrc` تعریف شوند.

> اطلاعات بیشتر: <https://tldp.org/LDP/abs/html/aliases.html>.

- نمایش تمامی نام های مستعار:

```bash
alias
```

- ایجاد یک نام مستعار:

```bash
alias word="command"
```

- نمایش نام مستعار مرتبط با کلمه مشخص شده:

```bash
alias word
```

- حذف یک نام مستعار:

```bash
unalias word
```

- تغییر `rm` به نسخه تعاملی با تعریف نام مستعار:

```bash
alias rm="rm -i"
```

- تعریف `la` به عنوان میانبری برای `ls -a`:

```bash
alias la="ls -a"
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | *: trim multiple spaces, fix line endings | 2021-04-04T01:44:24 | [04dd546e2de7](https://github.com/tldr-pages/tldr/commit/04dd546e2de7f59f40a867acca6f46b0dc8ea9b4)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | alias: add more information link (#5644) | 2021-03-30T20:57:29 | [edd9c5a5dc32](https://github.com/tldr-pages/tldr/commit/edd9c5a5dc32839ecf45b50d02d0260b8032002e)
[Taymaz Esmaeli](mailto:56496286+opoet7@users.noreply.github.com) | alias: add Persian translation (#5271) | 2021-02-17T13:54:07 | [e9c5dbb66390](https://github.com/tldr-pages/tldr/commit/e9c5dbb66390f9557469c83d74b53681e08cabab)

