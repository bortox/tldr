---
author: ['K.B.Dharun Krishna']
date: 1660217652
title: "dumpsys"
description: "dumpsys, ஆண்ட்ராய்டு சிஸ்டம் சேவைகள் பற்றிய தகவலை வழங்கவும்."
categories: "android"
---
> இந்தக் கட்டளையை `adb shell` மூலம் மட்டுமே பயன்படுத்த முடியும்.

> மேலும் விவரத்திற்கு: <https://developer.android.com/studio/command-line/dumpsys>.

- அனைத்து கணினி சேவைகளுக்கும் கண்டறியும் வெளியீட்டைப் பெறவும்:

```bash
dumpsys
```

- ஒரு குறிப்பிட்ட கணினி சேவைக்கான கண்டறியும் வெளியீட்டைப் பெறவும்:

```bash
dumpsys சேவை
```

- அனைத்து சேவைகளையும் பட்டியலிடுங்கள் `dumpsys` இதைப் பற்றிய தகவல்களை வழங்க முடியும்:

```bash
dumpsys -l
```

- ஒரு சேவைக்கான சேவை சார்ந்த வாதங்களைப் பட்டியலிடுங்கள்:

```bash
dumpsys சேவை -h
```

- கண்டறியும் வெளியீட்டில் இருந்து ஒரு குறிப்பிட்ட சேவையை விலக்கவும்:

```bash
dumpsys --skip சேவை
```

- நேரம் முடிவடையும் காலத்தை வினாடிகளில் குறிப்பிடவும் (இயல்புநிலையிலிருந்து 10 வினாடிகள் வரை):

```bash
dumpsys -t வினாடிகள்
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[K.B.Dharun Krishna](mailto:kbdharunkrishna@gmail.com) | android/*: add Tamil translation (#8337) | 2022-08-11T13:34:12 | [80f0129c7b3d](https://github.com/tldr-pages/tldr/commit/80f0129c7b3d8a56491c6cbda60c59815c987095)

