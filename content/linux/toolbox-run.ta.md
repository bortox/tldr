---
author: ['K.B.Dharun Krishna']
date: 1660307402
title: "toolbox run"
description: "toolbox run, ஏற்கனவே உள்ள `toolbox` கண்டெய்னரில் கட்டளையை இயக்கவும்."
categories: "linux"
---
> மேலும் பார்க்கவும்: `toolbox enter`.

> மேலும் விவரத்திற்கு: <https://manned.org/toolbox-run>.

- ஒரு குறிப்பிட்ட `toolbox` கொள்கலனில் ஒரு கட்டளையை இயக்கவும்:

```bash
toolbox run --container கொள்கலன்_பெயர் கட்டளை
```

- விநியோகத்தின் குறிப்பிட்ட வெளியீட்டிற்கு `toolbox` கொள்கலனுக்குள் கட்டளையை இயக்கவும்:

```bash
toolbox run --distro விநியோகம் --release வெளியீடு கட்டளை
```

- ஃபெடோரா 36க்கான இயல்புநிலை படத்தைப் பயன்படுத்தி `toolbox` கொள்கலனுக்குள் `emacs` ஐ இயக்கவும்:

```bash
toolbox run --distro fedora --release f36 emacs
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[K.B.Dharun Krishna](mailto:kbdharunkrishna@gmail.com) | toolbox*: add Tamil translation (#8338) | 2022-08-12T14:30:02 | [9eed96620776](https://github.com/tldr-pages/tldr/commit/9eed96620776be57b639c8afe583e620ba77b331)

