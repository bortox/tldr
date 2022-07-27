---
author: ['Arun Isaac']
date: 1636231346
title: "sha1sum, TLDR Pages"
description: "sha1sum, SHA1 மறையீட்டு சரிகாண்தொகையைக் கணி."
categories: "common"
---
> மேலும் விவரத்திற்கு: <https://www.gnu.org/software/coreutils/sha1sum>.

- கோப்பின் SHA1 சரிகாண்தொகையைக் கணி:

```bash
sha1sum கோப்பு
```

- பலக் கோப்புகளின் SHA1 சரிகாண்தொகையைக் கணி:

```bash
sha1sum கோப்பு1 கோப்பு2
```

- SHA1 சரிகாண்தொகைகளைக் கணித்து கோப்பில் எழுது:

```bash
sha1sum கோப்பு1 கோப்பு2 > கோப்பு.sha1
```

- SHA1 சரிகாண்தொகைகளுடைய கோப்பைப் படித்து கோப்புகளைச் சரிபார்:

```bash
sha1sum --check கோப்பு.sha1
```

- பிழையுற்ற கோப்புகளை மட்டும் காட்டு:

```bash
sha1sum --check --quiet கோப்பு.sha1
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Arun Isaac](mailto:arunisaac@users.noreply.github.com) | *sum: add Tamil translation (#7350) | 2021-11-06T21:42:26 | [029652c7825d](https://github.com/tldr-pages/tldr/commit/029652c7825dc93e497b59e990af16097f84bea0)

