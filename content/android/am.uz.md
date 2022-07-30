---
author: ['Javlon']
date: 1635360715
title: "am"
description: "am, Android faoliyat boshqaruvi."
categories: "android"
---
> Ko'proq malumot: <https://developer.android.com/studio/command-line/adb#am>.

- Anniq bir faoliyatni boshlash:

```bash
am start -n com.android.settings/.Settings
```

- Faoliyatni boshlash va unga malumot o'tkazish:

```bash
am start -a android.intent.action.VIEW -d tel:123
```

- Biron harakat va kategoriyaga mos keluvchi faoliyatni boshlash:

```bash
am start -a android.intent.action.MAIN -c android.intent.category.HOME
```

- Intentni URI ga o'zgartirish:

```bash
am to-uri -a android.intent.action.VIEW -d tel:123
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Javlon](mailto:56770292+javlonrahimov@users.noreply.github.com) | am, bugreport, bugreportz, cmd, dalvikvm, dumpsys: add Uzbek language (#7041) | 2021-10-27T20:51:55 | [90d0ec0491f0](https://github.com/tldr-pages/tldr/commit/90d0ec0491f0700ab86dd9a2cef848c38847c63f)

