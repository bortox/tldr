---
author: ['Arun Isaac']
date: 1636231346
title: "md5sum, TLDR Pages"
description: "md5sum, MD5 மறையீட்டு சரிகாண்தொகையைக் கணி."
categories: "common"
---
> மேலும் விவரத்திற்கு: <https://www.gnu.org/software/coreutils/md5sum>.

- கோப்பின் MD5 சரிகாண்தொகையைக் கணி:

```bash
md5sum கோப்பு
```

- பலக் கோப்புகளின் MD5 சரிகாண்தொகையைக் கணி:

```bash
md5sum கோப்பு1 கோப்பு2
```

- MD5 சரிகாண்தொகைகளுடைய கோப்பைப் படித்து கோப்புகளைச் சரிபார்:

```bash
md5sum -c கோப்பு.md5
```

- இயல் உள்ளீட்டின் MD5 சரிகாண்தொகையைக் கணி:

```bash
echo "உரை" | md5sum
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Arun Isaac](mailto:arunisaac@users.noreply.github.com) | *sum: add Tamil translation (#7350) | 2021-11-06T21:42:26 | [029652c7825d](https://github.com/tldr-pages/tldr/commit/029652c7825dc93e497b59e990af16097f84bea0)

