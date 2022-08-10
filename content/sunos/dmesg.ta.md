---
author: ['K.B.Dharun Krishna']
date: 1660082353
title: "dmesg"
description: "dmesg, கர்னல் செய்திகளை நிலையான வெளியீட்டிற்கு எழுதவும்."
categories: "sunos"
---
> மேலும் விவரத்திற்கு: <https://www.unix.com/man-page/sunos/1m/dmesg>.

- கர்னல் செய்திகளைக் காட்டு:

```bash
dmesg
```

- இந்த அமைப்பில் எவ்வளவு இயற்பியல் நினைவகம் உள்ளது என்பதைக் காட்டுங்கள்:

```bash
dmesg | grep -i memory
```

- ஒரு நேரத்தில் 1 பக்கம் கர்னல் செய்திகளைக் காட்டு:

```bash
dmesg | less
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[K.B.Dharun Krishna](mailto:kbdharunkrishna@gmail.com) | sunos/*: add Tamil translations (#8334) | 2022-08-09T23:59:13 | [8ae63c14d530](https://github.com/tldr-pages/tldr/commit/8ae63c14d5309ccfadecdede83eb544eae907175)

