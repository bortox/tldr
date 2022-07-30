---
author: ['Abd El-Twab M. Fakhry']
date: 1634005583
title: "gpasswd"
description: "gpasswd, إدارة `/etc/group` و `/etc/gshadow`."
categories: "linux"
---
> لمزيد من التفاصيل: <https://manned.org/gpasswd>.

- عرّف مديرين المجموعة المسماة:

```bash
sudo gpasswd -A مدير 2, مدير 1 مجموعة
```

- عين أعضاء المجموعة المسماة:

```bash
sudo gpasswd -M عضو 2, عضو 1 مجموعة
```

- إنشئ رقم سري للمجموعة المسماة:

```bash
gpasswd مجموعة
```

- أضف عضو إلي المجموعة المسماة:

```bash
gpasswd -a عضو مجموعة
```

- إحذف عضو من المجموعة المسماة:

```bash
gpasswd -d عضو مجموعة
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Abd El-Twab M. Fakhry](mailto:55063723+AbdeltwabMF@users.noreply.github.com) | gpasswd: add Arabic translation (#6819) | 2021-10-12T04:26:23 | [c3cf706923ee](https://github.com/tldr-pages/tldr/commit/c3cf706923ee0d9243d51c81a1091f6ccb906893)

