---
author: ['Arun Isaac', 'marchersimon', 'Dario Vladović', 'lincc']
date: 1643487459
title: "cp, TLDR Pages"
description: "cp, கோப்புகளையோ அடைவுகளையோ நகலெடு."
categories: "common"
---
> மேலும் விவரத்திற்கு: <https://www.gnu.org/software/coreutils/cp>.

- கோப்பை நகலெடு:

```bash
cp மூலக்கோப்பிற்குப்/பாதை நகல்/கோப்பிற்குப்/பாதை
```

- கோப்பை நகலெடுத்து அடைவொன்றிற்குள் அதே பெயருடன் வை:

```bash
cp மூலக்கோப்பிற்குப்/பாதை நகல்/கோப்பின்/தாயடைவிற்குப்/பாதை
```

- அடைவையும் அதில் உள்ளடங்கிய அனைத்தையும் தற்சுருளாக நகலெடு:

```bash
cp -r மூல/அடைவிற்குப்/பாதை நகல்/அடைவிற்குப்/பாதை
```

- அடைவையும் அதில் உள்ளடங்கிய அனைத்தையும் தற்சுருளாக வளவள நிலையில் (நகலெடுக்கப்படும் கோப்புகள் பட்டியலிடப்படும்) நகலெடு:

```bash
cp -vr மூல/அடைவிற்குப்/பாதை நகல்/அடைவிற்குப்/பாதை
```

- அடைவின் உள்ளடக்கத்தை நகலெடுத்து இன்னொரு அடைவிற்குள் வை:

```bash
cp -r மூல/அடைவிற்குப்/பாதை/* நகல்/அடைவிற்குப்/பாதை
```

- txt வகைப்பெயருடையக் கோப்புகளை ஊடாட்ட நிலையில் (ஏற்கனவே இருக்கும் கோப்புகள் மேலெழுதும் முன் உறுதிப்படுத்தக் கேட்கும்) நகலெடு:

```bash
cp -i *.txt நகல்/அடைவிற்குப்/பாதை
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[lincc](mailto:46962923+blueskyson@users.noreply.github.com) | *: update links via set-more-info-link.py (#7611) | 2022-01-29T21:17:39 | [b99f3da787c6](https://github.com/tldr-pages/tldr/commit/b99f3da787c6f43a545b9cb5ebd8265b1367fbc4)
[Dario Vladović](mailto:d.vladimyr@gmail.com) | coreutils*: use short more info links (#5658) | 2021-04-01T17:54:26 | [4830093903f6](https://github.com/tldr-pages/tldr/commit/4830093903f66ccf3ebbc2ecf477286e45edac59)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | cp: add more information link (#5556) | 2021-03-30T12:30:03 | [ad46ebe87a57](https://github.com/tldr-pages/tldr/commit/ad46ebe87a578bcb5e61d26addcf1bdfe287d75f)
[Arun Isaac](mailto:arunisaac@users.noreply.github.com) | cp,ls,mkdir,mv,rm,rmdir: add translations [Tamil](#2512) * cp: add Tamil page * ls: add Tamil page * mkdir: add Tamil page * mv: add [...] | 2018-11-05T23:46:16 | [356b346edf84](https://github.com/tldr-pages/tldr/commit/356b346edf841bf53a9a148c9a9b6a217c6ac6df)

