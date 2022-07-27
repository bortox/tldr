---
author: ['Arun Isaac', 'lincc']
date: 1643487459
title: "shasum, TLDR Pages"
description: "shasum, SHA மறையீட்டு சரிகாண்தொகைகளைக் கணி அல்லது சரிபார்."
categories: "common"
---
> மேலும் விவரத்திற்கு: <https://manned.org/shasum>.

- கோப்பின் SHA1 சரிகாண்தொகையைக் கணி:

```bash
shasum கோப்பு
```

- கோப்பின் SHA256 சரிகாண்தொகையைக் கணி:

```bash
shasum --algorithm 256 கோப்பு
```

- பலக் கோப்புகளின் SHA512 சரிகாண்தொகைகளைக் கணி:

```bash
shasum --algorithm 512 கோப்பு1 கோப்பு2
```

- SHA256 சரிகாண்தொகைகளைக் கணித்துக் கோப்பில் எழுது:

```bash
shasum --algorithm 256 கோப்பு1 கோப்பு2 > கோப்பு.sha256
```

- சரிகாண்தொகைகளுடைய கோப்பைப் படித்து கோப்புகளைச் சரிபார்:

```bash
shasum --check கோப்பு
```

- சரிகாண்தொகைகளைச் சரிபார்த்துப் பிழையுற்ற கோப்புகளை மட்டும் காட்டு:

```bash
shasum --check --quiet கோப்பு
```

- இயல் உள்ளீட்டின் SHA1 சரிகாண்தொகையைக் கணி:

```bash
கட்டளை | shasum
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[lincc](mailto:46962923+blueskyson@users.noreply.github.com) | *: update links via set-more-info-link.py (#7611) | 2022-01-29T21:17:39 | [b99f3da787c6](https://github.com/tldr-pages/tldr/commit/b99f3da787c6f43a545b9cb5ebd8265b1367fbc4)
[Arun Isaac](mailto:arunisaac@users.noreply.github.com) | *sum: add Tamil translation (#7350) | 2021-11-06T21:42:26 | [029652c7825d](https://github.com/tldr-pages/tldr/commit/029652c7825dc93e497b59e990af16097f84bea0)

