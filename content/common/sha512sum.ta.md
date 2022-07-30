---
author: ['Arun Isaac']
date: 1636231346
title: "sha512sum"
description: "sha512sum, SHA512 மறையீட்டு சரிகாண்தொகையைக் கணி."
categories: "common"
---
> மேலும் விவரத்திற்கு: <https://www.gnu.org/software/coreutils/manual/html_node/sha2-utilities.html>.

- கோப்பின் SHA512 சரிகாண்தொகையைக் கணி:

```bash
sha512sum கோப்பு
```

- பலக் கோப்புகளின் SHA512 சரிகாண்தொகையைக் கணி:

```bash
sha512sum கோப்பு1 கோப்பு2
```

- SHA512 சரிகாண்தொகைகளைக் கணித்து கோப்பில் எழுது:

```bash
sha512sum கோப்பு1 கோப்பு2 > கோப்பு.sha512
```

- SHA512 சரிகாண்தொகைகளுடைய கோப்பைப் படித்து கோப்புகளைச் சரிபார்:

```bash
sha512sum --check கோப்பு.sha512
```

- பிழையுற்ற கோப்புகளை மட்டும் காட்டு:

```bash
sha512sum --check --quiet கோப்பு.sha512
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Arun Isaac](mailto:arunisaac@users.noreply.github.com) | *sum: add Tamil translation (#7350) | 2021-11-06T21:42:26 | [029652c7825d](https://github.com/tldr-pages/tldr/commit/029652c7825dc93e497b59e990af16097f84bea0)

