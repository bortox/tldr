---
author: ['K.B.Dharun Krishna']
date: 1659700161
title: "gcc"
description: "gcc, C மற்றும் C++ மூலக் கோப்புகளை முன் செயலாக்கம் செய்து தொகுத்து, பின்னர் அவற்றைச் சேகரித்து இணைக்கவும்."
categories: "common"
---
> மேலும் தகவல்: <https://gcc.gnu.org>.

- பல மூல கோப்புகளை இயங்கக்கூடியதாக தொகுக்கவும்:

```bash
gcc பாதை/டு/மூல1.c பாதை/டு/மூல2.c ... --output பாதை/டு/வெளியீடு_இயங்கக்கூடியது
```

- வெளியீட்டில் எச்சரிக்கைகள் மற்றும் பிழைத்திருத்த குறியீடுகளை அனுமதிக்கவும்:

```bash
gcc பாதை/டு/மூல.c -Wall -Og --output பாதை/டு/வெளியீடு_இயங்கக்கூடியது
```

- வேறு பாதையிலிருந்து நூலகங்களைச் சேர்க்கவும்:

```bash
gcc பாதை/டு/மூல.c --output பாதை/டு/வெளியீடு_இயங்கக்கூடியது -Iபாதை/டு/தலைப்பு -Lபாதை/நூலகத்திற்கு -lநூலகம்_பெயர்
```

- மூலக் குறியீட்டை அசெம்பிளர் வழிமுறைகளில் தொகுக்கவும்:

```bash
gcc -S பாதை/டு/மூல.c
```

- இணைக்காமல் மூலக் குறியீட்டை தொகுக்கவும்:

```bash
gcc -c பாதை/டு/மூல.c
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[K.B.Dharun Krishna](mailto:kbdharunkrishna@gmail.com) | cc, g++, gcc: add Tamil translation (#8292) | 2022-08-05T13:49:21 | [6459d45c07b4](https://github.com/tldr-pages/tldr/commit/6459d45c07b42ebca4eabf405b78538e11f296d6)

