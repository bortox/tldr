---
author: ['Dario Vladović', 'lincc', 'Axel Navarro', 'Arun Isaac', 'marchersimon']
date: 1643487459
title: "ls"
description: "ls, அடைவு உள்ளடக்கத்தைப் பட்டியலிடு."
categories: "common"
---
> மேலும் விவரத்திற்கு: <https://www.gnu.org/software/coreutils/ls>.

- கோப்புகளை வரிக்கொன்றாகப் பட்டியலிடு:

```bash
ls -1
```

- மறைவான கோப்புகளுட்பட அனைத்துக் கோப்புகளையும் பட்டியலிடு:

```bash
ls -a
```

- அனைத்துக் கோப்புகளையும் முழு விவரங்களுடன் (அனுமதி, உடைமை, கோப்பளவு, மாற்றமைத்தத் தேதி) பட்டியலிடு:

```bash
ls -la
```

- கோப்பளவு படிப்பதற்கெளிய அலகுகளில் (KiB, MiB, GiB) காண்பிக்கப்பட்ட முழு விவரப் பட்டியல்:

```bash
ls -lh
```

- கோப்பளவால் இறங்குமுகமாக வரிசைப்படுத்தப்பட்ட முழு விவரப் பட்டியல்:

```bash
ls -lS
```

- மாற்றமைத்தத் தேதியால் காலவரிசைப்படுத்தப்பட்ட (பழையதிலிருந்துத் துவங்கி) முழு விவரப் பட்டியல்:

```bash
ls -ltr
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[lincc](mailto:46962923+blueskyson@users.noreply.github.com) | *: update links via set-more-info-link.py (#7611) | 2022-01-29T21:17:39 | [b99f3da787c6](https://github.com/tldr-pages/tldr/commit/b99f3da787c6f43a545b9cb5ebd8265b1367fbc4)
[Dario Vladović](mailto:d.vladimyr@gmail.com) | coreutils*: use short more info links (#5658) | 2021-04-01T17:54:26 | [4830093903f6](https://github.com/tldr-pages/tldr/commit/4830093903f66ccf3ebbc2ecf477286e45edac59)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | ls: add link (#5561) | 2021-03-30T09:12:42 | [a0e1beab9bd7](https://github.com/tldr-pages/tldr/commit/a0e1beab9bd704de488fefaca86d0c5e20a7a03b)
[Axel Navarro](mailto:navarroaxel@gmail.com) | ls: fix size units in example description (#5451) | 2021-03-15T20:57:50 | [8402bf0fa60e](https://github.com/tldr-pages/tldr/commit/8402bf0fa60e2e1d94b94c75aeceba8ed40fc409)
[Arun Isaac](mailto:arunisaac@users.noreply.github.com) | cp,ls,mkdir,mv,rm,rmdir: add translations [Tamil] (#2512) * cp: add Tamil page * ls: add Tamil page * mkdir: add Tamil page * mv: add [...] | 2018-11-05T23:46:16 | [356b346edf84](https://github.com/tldr-pages/tldr/commit/356b346edf841bf53a9a148c9a9b6a217c6ac6df)

