---
author: ['K.B.Dharun Krishna']
date: 1660908895
title: "fwupdmgr"
description: "fwupdmgr, `fwupd` ஐப் பயன்படுத்தி UEFI உட்பட சாதன நிலைபொருளைப் புதுப்பிப்பதற்கான ஒரு கருவி."
categories: "linux"
---
> மேலும் விவரத்திற்கு: <https://fwupd.org/>.

- fwupd மூலம் கண்டறியப்பட்ட அனைத்து சாதனங்களையும் காண்பி:

```bash
fwupdmgr get-devices
```

- LVFS இலிருந்து சமீபத்திய ஃபார்ம்வேர் மெட்டாடேட்டாவைப் பதிவிறக்கவும்:

```bash
fwupdmgr refresh
```

- உங்கள் கணினியில் உள்ள சாதனங்களுக்கு கிடைக்கும் புதுப்பிப்புகளை பட்டியலிடுங்கள்:

```bash
fwupdmgr get-updates
```

- ஃபார்ம்வேர் புதுப்பிப்புகளை நிறுவவும்:

```bash
fwupdmgr update
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[K.B.Dharun Krishna](mailto:kbdharunkrishna@gmail.com) | fdisk, fwupdmgr: add Tamil translation (#8371) | 2022-08-19T13:34:55 | [dfe8cd573cab](https://github.com/tldr-pages/tldr/commit/dfe8cd573cab2210356ff063219c19801ece899b)

