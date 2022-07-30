---
author: ['marchersimon', 'Arun Isaac', 'lincc']
date: 1643487459
title: "grep"
description: "grep, கோப்பில் தேடுகுறித்தொடர்களுடன் தேடு."
categories: "common"
---
> மேலும் விவரத்திற்கு: <https://www.gnu.org/software/grep/manual/grep.html>.

- கோப்பில் தேடு:

```bash
grep "தேடுதொடர்" கோப்பு
```

- தேடுகுறித்தொடரல்லா உருச்சரத்திற்குத் தேடு:

```bash
grep --fixed-strings "உருச்சரம்" கோப்பு
```

- அடைவிலும் சேய் அடைவுகளிலுமுள்ள இருமக் கோப்பல்லா அனைத்துக் கோப்புகளையும் தேடு; பொருத்தங்களின் வரி எண்ணைக் காட்டு:

```bash
grep --recursive --line-number --binary-files=without-match "தேடுதொடர்" அடைவு
```

- எழுத்துயர்நிலை கருதாது விரிவுபட்ட தேடுகுறித்தொடர்களுடன் (`?`, `+`, `{}`, `|` ஆகியவற்றைப் பயன்படுத்தலாம்) தேடு:

```bash
grep --extended-regexp --ignore-case "தேடுதொடர்" கோப்பு
```

- ஒவ்வொருப் பொருத்தத்திற்கும் சூழ்ந்த, முந்தைய அல்லது பிந்தைய 3 வரிகளைக் காட்டு:

```bash
grep --context|before-context|after-context=3 "தேடுதொடர்" கோப்பு
```

- ஒவ்வொருப் பொருத்தத்திற்கும் கோப்புப் பெயரையும் வரி எண்ணையும் காட்டு:

```bash
grep --with-filename --line-number "தேடுதொடர்" கோப்பு
```

- தேடுதொடருக்குத் தேடு, ஆனால் பொருந்திய பகுதிகளை மட்டும் காட்டு:

```bash
grep --only-matching "தேடுதொடர்" கோப்பு
```

- இயல் உள்ளீட்டில் தேடுதொடருக்குப் பொருந்தா வரிகளை மட்டும் காட்டு:

```bash
cat கோப்பு | grep --invert-match "தேடுதொடர்"
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[lincc](mailto:46962923+blueskyson@users.noreply.github.com) | *: update links via set-more-info-link.py (#7611) | 2022-01-29T21:17:39 | [b99f3da787c6](https://github.com/tldr-pages/tldr/commit/b99f3da787c6f43a545b9cb5ebd8265b1367fbc4)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: sync more information links in translations (#6537) | 2021-10-01T20:28:01 | [642dbf2e972e](https://github.com/tldr-pages/tldr/commit/642dbf2e972e388fab8c84ba3b4685fb862b6454)
[Arun Isaac](mailto:arunisaac@users.noreply.github.com) | grep: add Tamil translation (#6423) | 2021-08-30T13:42:15 | [3e5310c11c5f](https://github.com/tldr-pages/tldr/commit/3e5310c11c5fffed754090af0042b0efa04fd8d1)

