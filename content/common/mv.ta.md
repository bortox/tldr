---
author: ['Dario Vladović', 'Alessio', 'Arun Isaac', 'lincc']
date: 1643487459
title: "mv"
description: "mv, கோப்புகளையோ அடைவுகளையோ நகர்த்து அல்லது மறுபெயரிடு."
categories: "common"
---
> மேலும் விவரத்திற்கு: <https://www.gnu.org/software/coreutils/mv>.

- கோப்பை ஓரிடத்திலிருந்து இன்னோரிடத்திற்கு நகர்த்து:

```bash
mv மூலப்பாதை குறிபாதை
```

- ஏற்கனவே இருக்கும் கோப்புகள் மேலெழுதும் முன் உறுதிப்படுத்தாதே:

```bash
mv -f மூலப்பாதை குறிபாதை
```

- ஏற்கனவே இருக்கும் கோப்புகள் மேலெழுதும் முன் கோப்பு அனுமதிகளைப் பொருட்படுத்தாது உறுதிப்படுத்து:

```bash
mv -i மூலக்கோப்பு குறிகோப்பு
```

- ஏற்கனவே இருக்கும் கோப்புகள் மேலெழுதாதே:

```bash
mv -n மூலக்கோப்பு குறிகோப்பு
```

- கோப்புகளை வளவள நிலையில் (நகர்த்தப்படும் கோப்புகள் பட்டியலிடப்படும்) நகர்த்து:

```bash
mv -v மூலக்கோப்பு குறிகோப்பு
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[lincc](mailto:46962923+blueskyson@users.noreply.github.com) | *: update links via set-more-info-link.py (#7611) | 2022-01-29T21:17:39 | [b99f3da787c6](https://github.com/tldr-pages/tldr/commit/b99f3da787c6f43a545b9cb5ebd8265b1367fbc4)
[Dario Vladović](mailto:d.vladimyr@gmail.com) | coreutils*: use short more info links (#5658) | 2021-04-01T17:54:26 | [4830093903f6](https://github.com/tldr-pages/tldr/commit/4830093903f66ccf3ebbc2ecf477286e45edac59)
[Alessio](mailto:25589202+tomadojuice@users.noreply.github.com) | mv: add more information link (#5542) | 2021-03-29T20:24:45 | [45ff3b27a290](https://github.com/tldr-pages/tldr/commit/45ff3b27a290a760ee43340226e4e85e2091dbfc)
[Arun Isaac](mailto:arunisaac@users.noreply.github.com) | cp,ls,mkdir,mv,rm,rmdir: add translations [Tamil] (#2512) * cp: add Tamil page * ls: add Tamil page * mkdir: add Tamil page * mv: add [...] | 2018-11-05T23:46:16 | [356b346edf84](https://github.com/tldr-pages/tldr/commit/356b346edf841bf53a9a148c9a9b6a217c6ac6df)

