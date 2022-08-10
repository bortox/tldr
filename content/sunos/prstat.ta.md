---
author: ['K.B.Dharun Krishna']
date: 1660082353
title: "prstat"
description: "prstat, செயலில் உள்ள செயல்முறை புள்ளிவிவரங்களைப் புகாரளிக்கவும்."
categories: "sunos"
---
> மேலும் விவரத்திற்கு: <https://www.unix.com/man-page/sunos/1m/prstat>.

- CPU பயன்பாட்டின்படி வரிசைப்படுத்தப்பட்ட அனைத்து செயல்முறைகள் மற்றும் அறிக்கைகளின் புள்ளிவிவரங்களை ஆய்வு செய்யவும்:

```bash
prstat
```

- அனைத்து செயல்முறைகளையும் ஆய்வு செய்து, நினைவக பயன்பாட்டின்படி வரிசைப்படுத்தப்பட்ட புள்ளிவிவரங்களைப் புகாரளிக்கவும்:

```bash
prstat -s rss
```

- ஒவ்வொரு பயனருக்கும் மொத்த பயன்பாட்டுச் சுருக்கத்தைப் புகாரளிக்கவும்:

```bash
prstat -t
```

- மைக்ரோஸ்டேட் செயல்முறை கணக்கியல் தகவலைப் புகாரளிக்கவும்:

```bash
prstat -m
```

- ஒவ்வொரு நொடியும் செயல்முறைகளைப் பயன்படுத்தி முதல் 5 CPU இன் பட்டியலை அச்சிடவும்:

```bash
prstat -c -n 5 -s cpu 1
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[K.B.Dharun Krishna](mailto:kbdharunkrishna@gmail.com) | sunos/*: add Tamil translations (#8334) | 2022-08-09T23:59:13 | [8ae63c14d530](https://github.com/tldr-pages/tldr/commit/8ae63c14d5309ccfadecdede83eb544eae907175)

