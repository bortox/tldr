---
author: ['9tykeshav']
date: 1633878788
title: "clear"
description: "clear, टर्मिनल की स्क्रीन साफ़ करें।"
categories: "common"
---
> अधिक जानकारी: <https://manned.org/clear>।

- स्क्रीन साफ़ करें (बैश शेल में Control-L दबाने के बराबर):

```bash
clear
```

- स्क्रीन साफ़ करें लेकिन टर्मिनल का स्क्रॉलबैक बफ़र रखें:

```bash
clear -x
```

- साफ करने के लिए टर्मिनल के प्रकार को इंगित करें (डिफॉल्ट रूप से एनवायरमेंटल वरीबल `TERM` का मूल्य):

```bash
clear -T टर्मिनल_का_प्रकार
```

- `ncurses` का संस्करण दिखाएं जिसका उपयोग `clear` द्वारा किया गया है:

```bash
clear -V
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[9tykeshav](mailto:57292513+9tykeshav@users.noreply.github.com) | clear: add Hindi translation (#6872) | 2021-10-10T17:13:08 | [4e3390476f18](https://github.com/tldr-pages/tldr/commit/4e3390476f180310d197c850ef76bb1124a6adc4)

