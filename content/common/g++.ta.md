---
author: ['K.B.Dharun Krishna']
date: 1659905070
title: "g++"
description: "g++, C++ மூலக் கோப்புகளைத் தொகுக்கிறது."
categories: "common"
---
> GCC இன் பகுதி (GNU கம்பைலர் சேகரிப்பு).

> மேலும் விவரத்திற்கு: <https://gcc.gnu.org>.

- இயங்கக்கூடிய பைனரியில் ஒரு மூலக் குறியீடு கோப்பை தொகுக்கவும்:

```bash
g++ பாதை/டு/மூல.c -o பாதை/டு/வெளியீடு_இயங்கக்கூடியது
```

- அனைத்து பிழைகள் மற்றும் எச்சரிக்கைகள் (கிட்டத்தட்ட) காட்சி:

```bash
g++ பாதை/டு/மூல.c -Wall -o பாதை/டு/வெளியீடு_இயங்கக்கூடியது
```

- (C++98/C++11/C++14/C++17) தொகுக்க ஒரு மொழித் தரத்தைத் தேர்வு செய்யவும்:

```bash
g++ பாதை/டு/மூல.c -std=c++98|c++11|c++14|c++17 -o பாதை/டு/வெளியீடு_இயங்கக்கூடியது
```

- மூலக் கோப்பை விட வேறு பாதையில் அமைந்துள்ள நூலகங்களைச் சேர்க்கவும்:

```bash
g++ பாதை /டு/மூல.c -o {பாதை/டு/வெளியீடு_இயங்கக்கூடியது -Iபாதை/டு/தலைப்பு -Lபாதை/நூலகம் -lநூலகம்_பெயர்
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[K.B.Dharun Krishna](mailto:kbdharunkrishna@gmail.com) | pages.ta/*: fix more information Tamil translation (#8320) | 2022-08-07T22:44:30 | [e2a742ca82e2](https://github.com/tldr-pages/tldr/commit/e2a742ca82e2889a2d605962a45196e64b7579e4)
[K.B.Dharun Krishna](mailto:kbdharunkrishna@gmail.com) | cc, g++, gcc: add Tamil translation (#8292) | 2022-08-05T13:49:21 | [6459d45c07b4](https://github.com/tldr-pages/tldr/commit/6459d45c07b42ebca4eabf405b78538e11f296d6)

