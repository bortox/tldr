---
author: ['K.B.Dharun Krishna']
date: 1660082353
title: "devfsadm"
description: "devfsadm, `/dev` க்கான நிர்வாக கட்டளை. `/dev` பெயர்வெளியை பராமரிக்கிறது."
categories: "sunos"
---
> மேலும் விவரத்திற்கு: <https://www.unix.com/man-page/sunos/1m/devfsadm>.

- புதிய டிஸ்க்குகளை ஸ்கேன் செய்யவும்:

```bash
devfsadm -c disk
```

- தொங்கும் /தேவ் இணைப்புகளை சுத்தம் செய்து புதிய சாதனத்தை ஸ்கேன் செய்யவும்:

```bash
devfsadm -C -v
```

- ட்ரை-ரன் - என்ன மாற்றப்படும் என்பதை வெளியீடு ஆனால் எந்த மாற்றமும் செய்யாது:

```bash
devfsadm -C -v -n
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[K.B.Dharun Krishna](mailto:kbdharunkrishna@gmail.com) | sunos/*: add Tamil translations (#8334) | 2022-08-09T23:59:13 | [8ae63c14d530](https://github.com/tldr-pages/tldr/commit/8ae63c14d5309ccfadecdede83eb544eae907175)

