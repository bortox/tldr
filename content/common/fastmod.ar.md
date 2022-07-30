---
author: ['محمد الصوالحي', 'marchersimon']
date: 1659075216
title: "fastmod"
description: "fastmod, أداة للاستبدال الجزئي للنصوص في قاعدة الأكواد لديك."
categories: "common"
---
> التعبيرات النمطية يعالجها قفص من بضاعة رست وهو regex.

> لمزيد من التفاصيل: <https://github.com/facebookincubator/fastmod>.

- استبدال بالتعبيرات النمطية في كل ملفات المسار الحالي وأبنائه في الملفات غير المُتجاهلة بـ .ignore أو .gitignore:

```bash
fastmod تعبير_نمطي بديل
```

- استبدال متجاهلا حالة الحرف في ملف أو في ملفات مسار:

```bash
fastmod --ignore-case تعبير_نمطي بديل -- مسار/الـ/ملف مسار/الـ/السجل ...
```

- استبدال بالتعبيرات النمطية مع تحديد المكان الذي يُستبدل فيه:

```bash
fastmod تعبير_نمطي بديل --dir مسار/للـ/سجل --iglob '**/*.{js,json}'
```

- استبدال بالنص مُطابقةً (وليس التعبيرات النمطية)، في ملفات امتداداتهم إما js أو json فحسب:

```bash
fastmod --fixed-strings نص_مطابِق بديل -e json,js
```

- استبدال بجميع النصوص مُطابقةً، مباشرة دون مِحَثِّ تأكيد (prompt):

```bash
fastmod --accept-all --fixed-strings نص_مطابِق بديل
```

- استبدال بجميع النصوص مُطابقةً، مباشرة دون تأكيد، مع طباعة الملفات المُستبدل فيها:

```bash
fastmod --accept-all --print-changed-files --fixed-strings نص_مطابِق بديل
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | Sync more information links with all translations (#8256) | 2022-07-29T08:13:36 | [1f610a952ea0](https://github.com/tldr-pages/tldr/commit/1f610a952ea0d53e0a1bdbd1246ef81f24db2f3f)
[محمد الصوالحي](mailto:ms.2052001@gmail.com) | fastmod: add page (#7815) | 2022-03-09T11:58:38 | [37ab478d7988](https://github.com/tldr-pages/tldr/commit/37ab478d798855a43d0aea5f4e598825e30ec707)

