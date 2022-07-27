---
author: ['Arun Isaac', 'marchersimon', 'Dario Vladović', 'lincc']
date: 1643487459
title: "rm, TLDR Pages"
description: "rm, கோப்புகளையோ அடைவுகளையோ அழி."
categories: "common"
---
> மேலும் விவரத்திற்கு: <https://www.gnu.org/software/coreutils/rm>.

- கோப்புகளை அழி:

```bash
rm கோப்பொன்றிற்குப்/பாதை கோப்பின்னொன்றிற்குப்/பாதை
```

- அடைவொன்றையும் அதில் உள்ளடங்கிய அனைத்தையும் தற்சுருளாக அழி:

```bash
rm -r அடைவிற்குப்/பாதை
```

- உறுதிப்படுத்தக் கேட்காமலும் பிழை செய்திகளைக் காட்டாமலும் அடைவொன்றை அழி:

```bash
rm -rf அடைவிற்குப்/பாதை
```

- ஒவ்வொருக் கோப்பையும் அழிப்பதற்கு முன் உறுதிப்படுத்து:

```bash
rm -i கோப்புகள்
```

- கோப்புகளை வளவள நிலையில் (அழிக்கப்படும் கோப்புகள் பட்டியலிடப்படும்) அழி:

```bash
rm -v அடைவிற்குப்/பாதை/*
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[lincc](mailto:46962923+blueskyson@users.noreply.github.com) | *: update links via set-more-info-link.py (#7611) | 2022-01-29T21:17:39 | [b99f3da787c6](https://github.com/tldr-pages/tldr/commit/b99f3da787c6f43a545b9cb5ebd8265b1367fbc4)
[Dario Vladović](mailto:d.vladimyr@gmail.com) | coreutils*: use short more info links (#5658) | 2021-04-01T17:54:26 | [4830093903f6](https://github.com/tldr-pages/tldr/commit/4830093903f66ccf3ebbc2ecf477286e45edac59)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | rm: add link (#5552) | 2021-03-30T09:16:08 | [62668322a827](https://github.com/tldr-pages/tldr/commit/62668322a8278797489c72f005849770fe3f51fb)
[Arun Isaac](mailto:arunisaac@users.noreply.github.com) | cp,ls,mkdir,mv,rm,rmdir: add translations [Tamil](#2512) * cp: add Tamil page * ls: add Tamil page * mkdir: add Tamil page * mv: add [...] | 2018-11-05T23:46:16 | [356b346edf84](https://github.com/tldr-pages/tldr/commit/356b346edf841bf53a9a148c9a9b6a217c6ac6df)

