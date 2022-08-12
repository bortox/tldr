---
author: ['K.B.Dharun Krishna']
date: 1660217652
title: "pm"
description: "pm, ஆண்ட்ராய்டு சாதனத்தில் ஆப்ஸ் பற்றிய தகவலைக் காட்டவும்."
categories: "android"
---
> மேலும் விவரத்திற்கு: <https://developer.android.com/studio/command-line/adb#pm>.

- நிறுவப்பட்ட அனைத்து பயன்பாடுகளின் பட்டியலை அச்சிடவும்:

```bash
pm list packages
```

- நிறுவப்பட்ட அனைத்து கணினி பயன்பாடுகளின் பட்டியலை அச்சிடவும்:

```bash
pm list packages -s
```

- நிறுவப்பட்ட அனைத்து மூன்றாம் தரப்பு பயன்பாடுகளின் பட்டியலை அச்சிடவும்:

```bash
pm list packages -3
```

- குறிப்பிட்ட முக்கிய வார்த்தைகளுடன் பொருந்தக்கூடிய பயன்பாடுகளின் பட்டியலை அச்சிடவும்:

```bash
pm list packages முக்கிய_வார்த்தைகள்
```

- ஒரு குறிப்பிட்ட பயன்பாட்டின் APK இன் பாதையை அச்சிடவும்:

```bash
pm path செயலி
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[K.B.Dharun Krishna](mailto:kbdharunkrishna@gmail.com) | android/*: add Tamil translation (#8337) | 2022-08-11T13:34:12 | [80f0129c7b3d](https://github.com/tldr-pages/tldr/commit/80f0129c7b3d8a56491c6cbda60c59815c987095)

