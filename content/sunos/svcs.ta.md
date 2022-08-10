---
author: ['K.B.Dharun Krishna']
date: 1660082353
title: "svcs"
description: "svcs, இயங்கும் சேவைகள் பற்றிய தகவல்களை பட்டியலிடுங்கள்."
categories: "sunos"
---
> மேலும் விவரத்திற்கு: <https://www.unix.com/man-page/linux/1/svcs>.

- இயங்கும் அனைத்து சேவைகளையும் பட்டியலிடுங்கள்:

```bash
svcs
```

- இயங்காத சேவைகளை பட்டியலிடுங்கள்:

```bash
svcs -vx
```

- சேவையைப் பற்றிய தகவல்களைப் பட்டியலிடுங்கள்:

```bash
svcs apache
```

- சேவை பதிவு கோப்பின் இருப்பிடத்தைக் காட்டு:

```bash
svcs -L apache
```

- சேவை பதிவு கோப்பின் முடிவைக் காண்பி:

```bash
tail $(svcs -L apache)
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[K.B.Dharun Krishna](mailto:kbdharunkrishna@gmail.com) | sunos/*: add Tamil translations (#8334) | 2022-08-09T23:59:13 | [8ae63c14d530](https://github.com/tldr-pages/tldr/commit/8ae63c14d5309ccfadecdede83eb544eae907175)

