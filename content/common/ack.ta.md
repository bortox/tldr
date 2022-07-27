---
author: ['Marco Bonelli', 'lincc', 'GermanS', 'bl-ue', 'marchersimon']
date: 1643487459
title: "ack, TLDR Pages"
description: "ack, புரோகிராமர்களுக்கு உகந்ததாக கிரப் போன்ற தேடல் கருவி."
categories: "common"
---
> மேலும் விவரத்திற்கு: <https://beyondgrep.com/documentation>.

- "காலை" கொண்ட கோப்புகளைக் கண்டறியவும்:

```bash
ack காலை
```

- ஒரு குறிப்பிட்ட வகை கோப்புகளைக் கண்டறியவும்:

```bash
ack --ruby காலை
```

- "காலை" என்ற சொல்லின் மொத்த பொருத்தங்களை எண்ணிக்கையை எண்ணவும்:

```bash
ack -ch காலை
```

- காலை என்னும் சொல்லை கொண்ட ஒவ்வொரு கோப்பின் பெயர் மற்றும் பொருத்தங்களின் எண்ணிக்கையை காட்டவும்:

```bash
ack -cl காலை
```

- அனைத்து செல்லுபடியாகும் வகைகளையும் பட்டியலிடவும்:

```bash
ack --help-types
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[lincc](mailto:46962923+blueskyson@users.noreply.github.com) | *: update links via set-more-info-link.py (#7611) | 2022-01-29T21:17:39 | [b99f3da787c6](https://github.com/tldr-pages/tldr/commit/b99f3da787c6f43a545b9cb5ebd8265b1367fbc4)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: sync more information links in translations (#6537) | 2021-10-01T20:28:01 | [642dbf2e972e](https://github.com/tldr-pages/tldr/commit/642dbf2e972e388fab8c84ba3b4685fb862b6454)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | *: trim multiple spaces, fix line endings | 2021-04-04T01:44:24 | [04dd546e2de7](https://github.com/tldr-pages/tldr/commit/04dd546e2de7f59f40a867acca6f46b0dc8ea9b4)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | multiple pages: normalize "more information" labels (#5140) | 2021-01-15T18:24:49 | [c59f12aa9f55](https://github.com/tldr-pages/tldr/commit/c59f12aa9f55d85612ba22e4da86db293ff76977)
[GermanS](mailto:german.semenkov@gmail.com) | ack: fix typo (#4196) | 2020-07-16T23:33:06 | [ad248fb1170c](https://github.com/tldr-pages/tldr/commit/ad248fb1170c1bac38349a554cf3b37270747353)
[Marco Bonelli](mailto:mebeim@users.noreply.github.com) | ab, ack: add Tamil translation (revived) (#3761) Co-authored-by: MohamedSabthar <43032716+MohamedSabthar@users.noreply.github.com> | 2020-01-16T01:22:16 | [4ce320538293](https://github.com/tldr-pages/tldr/commit/4ce320538293541c474ed5e053c00e164d72a53f)

