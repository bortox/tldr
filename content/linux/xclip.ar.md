---
author: ['Abd El-Twab M. Fakhry']
date: 1633928777
title: "xclip, TLDR Pages"
description: "xclip, أداة معالجة لحافظة x11، تشبه إلي حد ما `xsel`."
categories: "linux"
---
> تتعامل مع الحافظة الأولية والثانوية لـ x، بالإضافة إلي حافظة النظام (`Ctrl + C`/`Ctrl + V`).

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
[Abd El-Twab M. Fakhry](mailto:55063723+AbdeltwabMF@users.noreply.github.com) | xclip: add Arabic translation (#6934) | 2021-10-11T07:06:17 | [cc97dde1f2f0](https://github.com/tldr-pages/tldr/commit/cc97dde1f2f0d062ab7d9bc579f5f7b25afdce3e)

