---
author: ['Karthikeyan Vaithilingam', 'lincc']
date: 1643487459
title: "git am, TLDR Pages"
description: "git am, பேட்ச் கோப்புகளைப் பயன்படுத்துங்கள். மின்னஞ்சல் வழியாக கமிட் பெறும்போது பயனுள்ளதாக இருக்கும்."
categories: "common"
---
> பேட்ச் கோப்புகளை உருவாக்கக்கூடிய `git format-patch` கட்டளையை காண்க.

> மேலும் விவரத்திற்கு: <https://git-scm.com/docs/git-am>.

- பேட்ச் கோப்பைப் பயன்படுத்துங்கள்:

```bash
git am கோப்புக்கான/பாதை/கோப்பு.patch
```

- பேட்ச் கோப்பைப் பயன்படுத்துவதற்கான செயல்முறையை நிறுத்தவும்:

```bash
git am --abort
```

- கோப்புகளை நிராகரிக்க தோல்வியுற்ற ஹன்களை சேமித்து, முடிந்தவரை ஒரு பேட்ச் கோப்பைப் பயன்படுத்துங்கள்:

```bash
git am --reject கோப்புக்கான/பாதை/கோப்பு.patch
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[lincc](mailto:46962923+blueskyson@users.noreply.github.com) | *: update links via set-more-info-link.py (#7611) | 2022-01-29T21:17:39 | [b99f3da787c6](https://github.com/tldr-pages/tldr/commit/b99f3da787c6f43a545b9cb5ebd8265b1367fbc4)
[Karthikeyan Vaithilingam](mailto:seenukarthi@gmail.com) | git-am: add Tamil translation Signed-off-by: Karthikeyan Vaithilingam <seenukarthi@gmail.com> | 2020-10-13T00:13:40 | [5096ed4652b5](https://github.com/tldr-pages/tldr/commit/5096ed4652b593782ddd3cc434363aa7b84a1602)

