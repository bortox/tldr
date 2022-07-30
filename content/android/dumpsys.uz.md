---
author: ['Javlon']
date: 1635360715
title: "dumpsys"
description: "dumpsys, Android tizimi xizmatlari to'g'risida malumot berish."
categories: "android"
---
> Bu buyruq faqatgina `adb shell` bilan ishlatiladi.

> Ko'proq malumot: <https://developer.android.com/studio/command-line/dumpsys>.

- Tizimning barcha xizmatlari haqida tahliliy malumot:

```bash
dumpsys
```

- Biron xizmat to'g'risida tahliliy malumot olish:

```bash
dumpsys service
```

- `dumpsys` buyrug'idagi barcha xizmatlarni chiqaradi:

```bash
dumpsys -l
```

- Xizmatning argumentlarini chiqaradi:

```bash
dumpsys service -h
```

- Tahliliy malumotlar ro'yhatidan biron xizmatni qoldirish:

```bash
dumpsys --skip service
```

- Time out ni belgilash (sekundlarda):

```bash
dumpsys -t sekund
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Javlon](mailto:56770292+javlonrahimov@users.noreply.github.com) | am, bugreport, bugreportz, cmd, dalvikvm, dumpsys: add Uzbek language (#7041) | 2021-10-27T20:51:55 | [90d0ec0491f0](https://github.com/tldr-pages/tldr/commit/90d0ec0491f0700ab86dd9a2cef848c38847c63f)

