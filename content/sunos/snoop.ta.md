---
author: ['K.B.Dharun Krishna']
date: 1660082353
title: "snoop"
description: "snoop, நெட்வொர்க் பாக்கெட் ஸ்னிஃபர்."
categories: "sunos"
---
> tcpdump சமமான SunOS.

> மேலும் விவரத்திற்கு: <https://www.unix.com/man-page/sunos/1m/snoop>.

- ஒரு குறிப்பிட்ட பிணைய இடைமுகத்தில் பாக்கெட்டுகளைப் பிடிக்கவும்:

```bash
snoop -d e1000g0
```

- கைப்பற்றப்பட்ட பாக்கெட்டுகளைக் காட்டுவதற்குப் பதிலாக ஒரு கோப்பில் சேமிக்கவும்:

```bash
snoop -o கோப்புப்_பெயர்
```

- ஒரு கோப்பிலிருந்து பாக்கெட்டுகளின் வெர்போஸ் புரோட்டோகால் லேயர் சுருக்கத்தைக் காண்பி:

```bash
snoop -V -i கோப்புப்_பெயர்
```

- ஹோஸ்ட்பெயரில் இருந்து வரும் நெட்வொர்க் பாக்கெட்டுகளைப் பிடித்து, கொடுக்கப்பட்ட போர்ட்டிற்குச் செல்லவும்:

```bash
snoop to port போர்ட் from host புரவலன்_பெயர்
```

- இரண்டு ஐபி முகவரிகளுக்கு இடையே பரிமாற்றம் செய்யப்பட்ட நெட்வொர்க் பாக்கெட்டுகளின் ஹெக்ஸ்-டம்ப்பைப் பிடித்துக் காட்டவும்:

```bash
snoop -x0 -p4 ஐபி_முகவரி_1 ஐபி_முகவரி_2
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[K.B.Dharun Krishna](mailto:kbdharunkrishna@gmail.com) | sunos/*: add Tamil translations (#8334) | 2022-08-09T23:59:13 | [8ae63c14d530](https://github.com/tldr-pages/tldr/commit/8ae63c14d5309ccfadecdede83eb544eae907175)

