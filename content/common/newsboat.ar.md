---
author: ['Abd El-Twab M. Fakhry']
date: 1635185003
title: "newsboat"
description: "newsboat, هو قارئ خلاصة آر إس إس للطرفية أو الكونسول."
categories: "common"
---
> لمزيد من التفاصيل: <https://newsboat.org/>.

- إستيراد روابط الخلاصات من ملف OPML:

```bash
newsboat -i الخلاصات.xml
```

- إضافة روابط الخلاصات يدوياً:

```bash
echo http://مثال.com/الخلاصة/إلي/المسار >> "${HOME}/.newsboat/urls"
```

- إبدأ newsboat وقم بتحديث كل الخلاصات عند بدء التشغيل:

```bash
newsboat -r
```

- نفذ أمر أو عدة أوامر مفصولة بمسافات بدون الحاجة إلي فتح newsboat:

```bash
newsboat -x reload print-unread ...
```

- انظر إختصارات لوحة المفاتيح (الإختصارت الأكثر شيوعاً مرئية في شريط الحالة):

```bash
?
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Abd El-Twab M. Fakhry](mailto:55063723+AbdeltwabMF@users.noreply.github.com) | newsboat: add Arabic translation (#7117) | 2021-10-25T20:03:23 | [ac6515451b45](https://github.com/tldr-pages/tldr/commit/ac6515451b45e3291863ae1bc5aa37b42ea31c53)

