---
author: ['Karthikeyan Vaithilingam', 'lincc']
date: 1643487459
title: "git clone"
description: "git clone, ஏற்கனவே உள்ள ஒரு களஞ்சியத்தை குளோன் செய்யுங்கள்."
categories: "common"
---
> மேலும் விவரத்திற்கு: <https://git-scm.com/docs/git-clone>.

- ஏற்கனவே உள்ள ஒரு களஞ்சியத்தை குளோன் செய்யுங்கள்:

```bash
git clone தொலை_களஞ்சிய_இடம்
```

- இருக்கும் களஞ்சியத்தையும் அதன் துணை தொகுதிகளையும் குளோன் செய்யுங்கள்:

```bash
git clone --recursive தொலை_களஞ்சிய_இடம்
```

- கணினியில் உள்ள ஒரு களஞ்சியத்தை குளோன் செய்யுங்கள்:

```bash
git clone -l கணினியில்/உள்ள/களஞ்சியத்தின்/பாதை
```

- அமைதியாக குளோன்:

```bash
git clone -q தொலை_களஞ்சிய_இடம்
```

- இயல்புநிலை கிளையில் மிகச் சமீபத்திய 10 கமிட்டுகளை மட்டுமே பெறும் களஞ்சியத்தை குளோன் செய்யுங்கள் (நேரத்தைச் சேமிக்க பயனுள்ளதாக இருக்கும்):

```bash
git clone --depth 10 தொலை_களஞ்சிய_இடம்
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[lincc](mailto:46962923+blueskyson@users.noreply.github.com) | *: update links via set-more-info-link.py (#7611) | 2022-01-29T21:17:39 | [b99f3da787c6](https://github.com/tldr-pages/tldr/commit/b99f3da787c6f43a545b9cb5ebd8265b1367fbc4)
[Karthikeyan Vaithilingam](mailto:seenukarthi@gmail.com) | git-clone: add Tamil translation Signed-off-by: Karthikeyan Vaithilingam <seenukarthi@gmail.com> | 2020-10-13T00:13:40 | [156f2f0ef334](https://github.com/tldr-pages/tldr/commit/156f2f0ef334a11f7e3f9835501e8135a85f8e70)

