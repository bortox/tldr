---
author: ['Abd El-Twab M. Fakhry']
date: 1633530256
title: "dockerd"
description: "dockerd, هي عملية مستمرة تعمل في الخلفية تبدأها لتتحكم في حاويات الدوكر."
categories: "linux"
---
> لمزيد من التفاصيل: <https://docs.docker.com/engine/reference/commandline/dockerd/>.

- قم بتشغيل دوكر في الخلفية:

```bash
dockerd
```

- قم بتشغيل دوكر في الخلفية واجعله يستمع علي منفذ معين (يونكس وبروتوكول ضبط الإرسال):

```bash
dockerd --host unix://السوكيت/إلي/المسار --host tcp://ip
```

- قم بتشغيل دوكر في الخلفية برقم عملية معين:

```bash
dockerd --pidfile ملف_رقم_العملية/إلي/المسار
```

- قم بتشغيل دوكر في وضع التصحيح واكتشاف الأخطاء:

```bash
dockerd --debug
```

- قم بتشغيل دوكر وحدد له مستوي سجل معين:

```bash
dockerd --log-level=debug|info|warn|error|fatal
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Abd El-Twab M. Fakhry](mailto:55063723+AbdeltwabMF@users.noreply.github.com) | dockerd: add Arabic translation (#6822) | 2021-10-06T16:24:16 | [178e1a1513f1](https://github.com/tldr-pages/tldr/commit/178e1a1513f1bb9660a39b6d9c09906fec52d3e5)

