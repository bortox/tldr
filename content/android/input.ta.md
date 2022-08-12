---
author: ['K.B.Dharun Krishna']
date: 1660217652
title: "input"
description: "input, நிகழ்வுக் குறியீடுகள் அல்லது தொடுதிரை சைகைகளை ஆண்ட்ராய்டு சாதனத்திற்கு அனுப்பவும்."
categories: "android"
---
> இந்தக் கட்டளையை `adb shell` மூலம் மட்டுமே பயன்படுத்த முடியும்.

> மேலும் விவரத்திற்கு: <https://developer.android.com/reference/android/view/KeyEvent.html#constants_1>.

- ஆண்ட்ராய்டு சாதனத்திற்கு ஒற்றை எழுத்துக்கான நிகழ்வுக் குறியீட்டை அனுப்பவும்:

```bash
input keyevent நிகழ்வு_குறியீடு
```

- ஆண்ட்ராய்டு சாதனத்திற்கு உரையை அனுப்பு (`%s` என்பது இடைவெளிகளைக் குறிக்கிறது):

```bash
input text "உரை"
```

- ஆண்ட்ராய்டு சாதனத்திற்கு ஒரு முறை தட்டவும்:

```bash
input tap எக்ஸ்_போஸ் ஒய்_போஸ்
```

- ஆண்ட்ராய்டு சாதனத்திற்கு ஸ்வைப் சைகையை அனுப்பவும்:

```bash
input swipe எக்ஸ்_தொடக்கம் ஒய்_தொடக்கம் எக்ஸ்_முடிவு ஒய்_முடிவு காலம்_மில்லி_வினாடியில்
```

- ஸ்வைப் சைகையைப் பயன்படுத்தி ஆண்ட்ராய்டு சாதனத்திற்கு நீண்ட அழுத்தத்தை அனுப்பவும்:

```bash
input swipe எக்ஸ்_போஸ் ஒய்_போஸ் எக்ஸ்_போஸ் ஒய்_போஸ் காலம்_மில்லி_வினாடியில்
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[K.B.Dharun Krishna](mailto:kbdharunkrishna@gmail.com) | android/*: add Tamil translation (#8337) | 2022-08-11T13:34:12 | [80f0129c7b3d](https://github.com/tldr-pages/tldr/commit/80f0129c7b3d8a56491c6cbda60c59815c987095)

