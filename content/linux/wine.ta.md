---
author: ['K.B.Dharun Krishna']
date: 1659619745
title: "wine"
description: "wine, யூனிக்ஸ் அடிப்படையிலான கணினிகளில் விண்டோஸ் இயங்குதளங்களை இயக்கவும்."
categories: "linux"
---
> மேலும் தகவல்: <https://wiki.winehq.org/>.

- `wine` சூழலில் ஒரு குறிப்பிட்ட நிரலை இயக்கவும்::

```bash
wine கட்டளை
```

- பின்னணியில் ஒரு குறிப்பிட்ட நிரலை இயக்கவும்:

```bash
wine start கட்டளை
```

- ஒரு MSI தொகுப்பை நிறுவவும்/நிறுத்தவும்:

```bash
wine msiexec /i|x கோப்போ/அடைவோ/நிரல்தொகுப்பு.msi
```

- `கோப்பு எக்ஸ்ப்ளோரர்`, `நோட்பேட்` அல்லது `வேர்ட்பேட்` ஐ இயக்கவும்:

```bash
wine explorer|notepad|write
```

- `ரெஜிஸ்ட்ரி எடிட்டர்`, `கண்ட்ரோல் பேனல்` அல்லது `டாஸ்க் மேனேஜர்` ஆகியவற்றை இயக்கவும்:

```bash
wine regedit|control|taskmgr
```

- கட்டமைப்பு கருவியை இயக்கவும்:

```bash
wine winecfg
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[K.B.Dharun Krishna](mailto:kbdharunkrishna@gmail.com) | wine: add Tamil translation (#8295) | 2022-08-04T15:29:05 | [ac73ace14e86](https://github.com/tldr-pages/tldr/commit/ac73ace14e862aa28852ad19e45c78f44989f6b1)

