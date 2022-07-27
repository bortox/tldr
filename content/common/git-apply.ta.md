---
author: ['Karthikeyan Vaithilingam', 'lincc']
date: 1643487459
title: "git apply, TLDR Pages"
description: "git apply, கோப்புகள் மற்றும் / அல்லது குறியீட்டுக்கு ஒரு இணைப்பு பயன்படுத்தவும்."
categories: "common"
---
> மேலும் விவரத்திற்கு: <https://git-scm.com/docs/git-apply>.

- இணைக்கப்பட்ட கோப்புகளைப் பற்றிய செய்திகளை அச்சிடுங்கள்:

```bash
git apply --verbose கோப்புக்கான/பாதை
```

- இணைக்கப்பட்ட கோப்புகளை குறியீட்டில் பயன்படுத்தவும் மற்றும் சேர்க்கவும்:

```bash
git apply --index கோப்புக்கான/பாதை
```

- ரிமோட் பேட்ச் கோப்பைப் பயன்படுத்துங்கள்:

```bash
curl https://example.com/கோப்பு.patch | git apply
```

- உள்ளீட்டிற்கான வெளியீட்டு வேறுபாடு நிலை மற்றும் இணைப்பு பொருந்தும்:

```bash
git apply --stat --apply கோப்புக்கான/பாதை
```

- பேட்சை தலைகீழாகப் பயன்படுத்துங்கள்:

```bash
git apply --reverse கோப்புக்கான/பாதை
```

- பேட்ச் முடிவை குறியீட்டில் வேலை செய்யும் மரத்தை மாற்றாமல் சேமிக்கவும்:

```bash
git apply --cache கோப்புக்கான/பாதை
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[lincc](mailto:46962923+blueskyson@users.noreply.github.com) | *: update links via set-more-info-link.py (#7611) | 2022-01-29T21:17:39 | [b99f3da787c6](https://github.com/tldr-pages/tldr/commit/b99f3da787c6f43a545b9cb5ebd8265b1367fbc4)
[Karthikeyan Vaithilingam](mailto:seenukarthi@gmail.com) | git-apply: add Tamil translation Signed-off-by: Karthikeyan Vaithilingam <seenukarthi@gmail.com> | 2020-10-13T00:13:40 | [e311d4833993](https://github.com/tldr-pages/tldr/commit/e311d48339939a47e40aa6e14972d3845d9b706d)

