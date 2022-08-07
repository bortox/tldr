---
author: ['K.B.Dharun Krishna']
date: 1659802437
title: "uname"
description: "uname, தற்போதைய இயந்திரம் மற்றும் அதில் இயங்கும் இயக்க முறைமை பற்றிய விவரங்களை அச்சிடவும்."
categories: "common"
---
> `lsb_release` ஐயும் பார்க்கவும்.

> மேலும் தகவல்: <https://www.gnu.org/software/coreutils/uname>.

- கர்னல் பெயரை அச்சிடவும்:

```bash
uname
```

- கணினி கட்டமைப்பு மற்றும் செயலி தகவலை அச்சிடவும்:

```bash
uname --machine --processor
```

- கர்னல் பெயர், கர்னல் வெளியீடு மற்றும் கர்னல் பதிப்பை அச்சிடவும்:

```bash
uname --kernel-name --kernel-release --kernel-version
```

- அச்சு அமைப்பு ஹோஸ்ட்பெயரை:

```bash
uname --nodename
```

- கிடைக்கக்கூடிய அனைத்து கணினி தகவல்களையும் அச்சிடவும்:

```bash
uname --all
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[K.B.Dharun Krishna](mailto:kbdharunkrishna@gmail.com) | uname: add Tamil translation (#8282) | 2022-08-06T18:13:57 | [3d4954235c9e](https://github.com/tldr-pages/tldr/commit/3d4954235c9e40cbba55f8a723e9eebd18e3d04e)

