---
author: ['K.B.Dharun Krishna']
date: 1660082353
title: "prctl"
description: "prctl, இயங்கும் செயல்முறைகளின், பணிகள் மற்றும் திட்டங்களின் ஆதாரக் கட்டுப்பாடு பெறவும் அல்லது அமைக்கவும்."
categories: "sunos"
---
> மேலும் விவரத்திற்கு: <https://www.unix.com/man-page/sunos/1/prctl>.

- செயல்முறை வரம்புகள் மற்றும் அனுமதிகளை ஆய்வு செய்:

```bash
prctl PID
```

- இயந்திர பாகுபடுத்தக்கூடிய வடிவத்தில் செயல்முறை வரம்புகள் மற்றும் அனுமதிகளை ஆய்வு செய்:

```bash
prctl -P PID
```

- இயங்கும் செயல்முறைக்கான குறிப்பிட்ட வரம்பைப் பெறுங்கள்:

```bash
prctl -n process.max-file-descriptor PID
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[K.B.Dharun Krishna](mailto:kbdharunkrishna@gmail.com) | sunos/*: add Tamil translations (#8334) | 2022-08-09T23:59:13 | [8ae63c14d530](https://github.com/tldr-pages/tldr/commit/8ae63c14d5309ccfadecdede83eb544eae907175)

