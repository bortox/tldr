---
author: ['K.B.Dharun Krishna']
date: 1660217652
title: "am"
description: "am, ஆண்ட்ராய்டு செயல்பாட்டு மேலாளர்."
categories: "android"
---
> மேலும் விவரத்திற்கு: <https://developer.android.com/studio/command-line/adb#am>.

- ஒரு குறிப்பிட்ட செயல்பாட்டைத் தொடங்கவும்:

```bash
am start -n com.android.settings/.Settings
```

- ஒரு செயல்பாட்டைத் தொடங்கி, அதற்குத் தரவை அனுப்பவும்:

```bash
am start -a android.intent.action.VIEW -d tel:123
```

- குறிப்பிட்ட செயலுக்கும் வகைக்கும் பொருந்தும் செயல்பாட்டைத் தொடங்கவும்:

```bash
am start -a android.intent.action.MAIN -c android.intent.category.HOME
```

- ஒரு நோக்கத்தை URI ஆக மாற்றவும்:

```bash
am to-uri -a android.intent.action.VIEW -d tel:123
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[K.B.Dharun Krishna](mailto:kbdharunkrishna@gmail.com) | android/*: add Tamil translation (#8337) | 2022-08-11T13:34:12 | [80f0129c7b3d](https://github.com/tldr-pages/tldr/commit/80f0129c7b3d8a56491c6cbda60c59815c987095)

