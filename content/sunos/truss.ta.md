---
author: ['K.B.Dharun Krishna']
date: 1660082353
title: "truss"
description: "truss, சிஸ்டம் அழைப்புகளைத் தடமறிவதற்கான பிழைகாணல் கருவி."
categories: "sunos"
---
> ஸ்டிரேஸுக்குச் சமமான SunOS.

> மேலும் விவரத்திற்கு: <https://www.unix.com/man-page/linux/1/truss>.

- அனைத்து குழந்தை செயல்முறைகளையும் பின்பற்றி, அதை செயல்படுத்துவதன் மூலம் ஒரு நிரலைக் கண்டறியத் தொடங்குங்கள்:

```bash
truss -f நிரல்
```

- ஒரு குறிப்பிட்ட செயல்முறையை அதன் PID மூலம் கண்டறியத் தொடங்குங்கள்:

```bash
truss -p pid
```

- ஒரு நிரலை இயக்குவதன் மூலம், வாதங்கள் மற்றும் சூழல் மாறிகளைக் காண்பிப்பதன் மூலம் அதைக் கண்டுபிடிக்கத் தொடங்குங்கள்:

```bash
truss -a -e நிரல்
```

- ஒவ்வொரு கணினி அழைப்பிற்கும் நேரம், அழைப்புகள் மற்றும் பிழைகளை எண்ணி, நிரல் வெளியேறும் போது சுருக்கத்தைப் புகாரளிக்கவும்:

```bash
truss -c -p pid
```

- கணினி அழைப்பின் மூலம் செயல்முறை வடிகட்டுதல் வெளியீட்டைக் கண்டறியவும்:

```bash
truss -p pid -t அமைப்பின்_அழைப்பு_பெயர்
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[K.B.Dharun Krishna](mailto:kbdharunkrishna@gmail.com) | sunos/*: add Tamil translations (#8334) | 2022-08-09T23:59:13 | [8ae63c14d530](https://github.com/tldr-pages/tldr/commit/8ae63c14d5309ccfadecdede83eb544eae907175)

