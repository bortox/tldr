---
author: ['Arun Isaac']
date: 1636231346
title: "b2sum, TLDR Pages"
description: "b2sum, BLAKE2 மறையீட்டு சரிகாண்தொகையைக் கணி."
categories: "common"
---
> மேலும் விவரத்திற்கு: <https://www.gnu.org/software/coreutils/b2sum>.

- கோப்பின் BLAKE2 சரிகாண்தொகையைக் கணி:

```bash
b2sum கோப்பு
```

- பலக் கோப்புகளின் BLAKE2 சரிகாண்தொகையைக் கணி:

```bash
b2sum கோப்பு1 கோப்பு2
```

- BLAKE2 சரிகாண்தொகைகளுடைய கோப்பைப் படித்து கோப்புகளைச் சரிபார்:

```bash
b2sum -c கோப்பு.b2
```

- இயல் உள்ளீட்டின் BLAKE2 சரிகாண்தொகையைக் கணி:

```bash
கட்டளை | b2sum
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Arun Isaac](mailto:arunisaac@users.noreply.github.com) | *sum: add Tamil translation (#7350) | 2021-11-06T21:42:26 | [029652c7825d](https://github.com/tldr-pages/tldr/commit/029652c7825dc93e497b59e990af16097f84bea0)

