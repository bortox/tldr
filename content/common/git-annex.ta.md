---
author: ['Karthikeyan Vaithilingam', 'lincc']
date: 1643487459
title: "git annex, TLDR Pages"
description: "git annex, கோப்புகளை அவற்றின் உள்ளடக்கங்களை சரிபார்க்காமல், ஜிட் மூலம் நிர்வகிக்கவும்."
categories: "common"
---
> ஒரு கோப்பு இணைக்கப்படும்போது, ​​அதன் உள்ளடக்கம் ஒரு முக்கிய மதிப்புக் கடைக்கு நகர்த்தப்படும், மேலும் உள்ளடக்கத்தை சுட்டிக்காட்டும் ஒரு சிம்லிங்க் செய்யப்படுகிறது.

> மேலும் விவரத்திற்கு: <https://git-annex.branchable.com>.

- உதவி:

```bash
git annex help
```

- `git annex` உடன் ஒரு களஞ்சியத்தை தொடங்கவும்:

```bash
git annex init
```

- ஒரு கோப்பைச் சேர்க்கவும்:

```bash
git annex add கோப்பு_அல்லது_கோப்பகத்திற்கான/பாதை
```

- ஒரு கோப்பு அல்லது கோப்பகத்தின் தற்போதைய நிலையைக் காட்டு:

```bash
git annex status கோப்பு_அல்லது_கோப்பகத்திற்கான/பாதை
```

- தொலைநிலையுடன் உள்ளூர் களஞ்சியத்தை ஒத்திசைக்கவும்:

```bash
git annex தொலைநிலை
```

- ஒரு கோப்பு அல்லது கோப்பகத்தைப் பெறுங்கள்:

```bash
git annex get கோப்பு_அல்லது_கோப்பகத்திற்கான/பாதை
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[lincc](mailto:46962923+blueskyson@users.noreply.github.com) | *: update links via set-more-info-link.py (#7611) | 2022-01-29T21:17:39 | [b99f3da787c6](https://github.com/tldr-pages/tldr/commit/b99f3da787c6f43a545b9cb5ebd8265b1367fbc4)
[Karthikeyan Vaithilingam](mailto:seenukarthi@gmail.com) | git-annex: add Tamil translation Signed-off-by: Karthikeyan Vaithilingam <seenukarthi@gmail.com> | 2020-10-13T00:13:40 | [546b5490c2a2](https://github.com/tldr-pages/tldr/commit/546b5490c2a2be0a0f53f612653970cfdc35b535)

