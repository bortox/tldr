---
author: ['K.B.Dharun Krishna']
date: 1660217652
title: "settings"
description: "settings, ஆண்ட்ராய்டு ஓஎஸ் பற்றிய தகவல்களைப் பெறுங்கள்."
categories: "android"
---
> மேலும் விவரத்திற்கு: <https://adbinstaller.com/commands/adb-shell-settings-5b670d5ee7958178a2955536>.

- `குளோபல்` பெயர்வெளியில் அமைப்புகளின் பட்டியலைக் காண்பி:

```bash
settings list குளோபல்
```

- ஒரு குறிப்பிட்ட அமைப்பின் மதிப்பைப் பெறவும்:

```bash
settings get குளோபல் விமானம்_முறை_ஆன்
```

- அமைப்பின் மதிப்பை அமைக்கவும்:

```bash
settings put குளோபல் திரை_பிரகாசம் 42
```

- Delete a specific setting:

```bash
settings delete பாதுகாப்பான திரை_சேமிப்பான்_இயக்கப்பட்டது
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[K.B.Dharun Krishna](mailto:kbdharunkrishna@gmail.com) | android/*: add Tamil translation (#8337) | 2022-08-11T13:34:12 | [80f0129c7b3d](https://github.com/tldr-pages/tldr/commit/80f0129c7b3d8a56491c6cbda60c59815c987095)

