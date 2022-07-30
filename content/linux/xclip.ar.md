---
author: ['Abd El-Twab M. Fakhry', 'marchersimon']
date: 1659075216
title: "xclip, TLDR Pages"
description: "xclip, أداة معالجة لحافظة x11، تشبه إلي حد ما `xsel`."
categories: "linux"
---
> تتعامل مع الحافظة الأولية والثانوية لـ x، بالإضافة إلي حافظة النظام (`Ctrl + C`/`Ctrl + V`).

> لمزيد من التفاصيل: <https://manned.org/xclip>.

- إنسخ ناتج الخرج من أمر إلي حافظة x11 الأولية:

```bash
echo 123 | xclip
```

- إنسخ ناتج الخرج من أمر إلي الحافظة المختارة:

```bash
echo 123 | xclip -selection primary|secondary|clipboard
```

- إنسخ ناتج الخرج من أمر إلي حافظة النظام، باستخدام الصيغة المختصرة:

```bash
echo 123 | xclip -sel clip
```

- إنسخ محتوي ملف إلي حافظة النظام:

```bash
xclip -sel clip اسم_الملف.txt
```

- إنسخ محتوي صورة بصيغة PNG إلي حافظة النظام (يمكن أن تستخدم في أي برنامج عن طريق لصق):

```bash
xclip -sel clip -t image/png اسم_الملف.png
```

- إنسخ إدخال المستخدم في الطرفية أو الكونسول إلي حافظة النظام:

```bash
xclip -i
```

- إلصق محتوي حافظة x11 الأولية إلي الطرفية أو الكونسول:

```bash
xclip -o
```

- إلصق محتوي حافظة النظام إلي الطرفية أو الكونسول:

```bash
xclip -o -sel clip
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | Sync more information links with all translations (#8256) | 2022-07-29T08:13:36 | [1f610a952ea0](https://github.com/tldr-pages/tldr/commit/1f610a952ea0d53e0a1bdbd1246ef81f24db2f3f)
[Abd El-Twab M. Fakhry](mailto:55063723+AbdeltwabMF@users.noreply.github.com) | xclip: add Arabic translation (#6934) | 2021-10-11T07:06:17 | [cc97dde1f2f0](https://github.com/tldr-pages/tldr/commit/cc97dde1f2f0d062ab7d9bc579f5f7b25afdce3e)

