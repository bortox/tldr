---
author: ['K.B.Dharun Krishna']
date: 1660082353
title: "svccfg"
description: "svccfg, சேவை உள்ளமைவுகளை இறக்குமதி செய்யவும், ஏற்றுமதி செய்யவும் மற்றும் மாற்றவும்."
categories: "sunos"
---
> மேலும் விவரத்திற்கு: <https://www.unix.com/man-page/linux/1m/svccfg>.

- உள்ளமைவு கோப்பை சரிபார்க்கவும்:

```bash
svccfg validate smf.xml
```

- கோப்பிற்கு சேவை உள்ளமைவுகளை ஏற்றுமதி செய்யவும்:

```bash
svccfg export சேவை_பெயர் > smf.xml
```

- கோப்பிலிருந்து சேவை உள்ளமைவுகளை இறக்குமதி/புதுப்பித்தல்:

```bash
svccfg import smf.xml
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[K.B.Dharun Krishna](mailto:kbdharunkrishna@gmail.com) | sunos/*: add Tamil translations (#8334) | 2022-08-09T23:59:13 | [8ae63c14d530](https://github.com/tldr-pages/tldr/commit/8ae63c14d5309ccfadecdede83eb544eae907175)

