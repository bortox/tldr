---
author: ['Karthikeyan Vaithilingam', 'lincc']
date: 1643487459
title: "git archive, TLDR Pages"
description: "git archive, பெயரிடப்பட்ட மரத்திலிருந்து கோப்புகளின் காப்பகத்தை உருவாக்கவும்."
categories: "common"
---
> மேலும் விவரத்திற்கு: <https://git-scm.com/docs/git-archive>.

- தற்போதைய HEAD இன் உள்ளடக்கங்களிலிருந்து ஒரு தார் காப்பகத்தை உருவாக்கி அதை நிலையான வெளியீட்டில் அச்சிடுக:

```bash
git archive --verbose HEAD
```

- தற்போதைய HEAD இலிருந்து ஒரு ஜிப் காப்பகத்தை உருவாக்கி அதை நிலையான வெளியீட்டில் அச்சிடுக:

```bash
git archive --verbose --format=zip HEAD
```

- மேலே உள்ளதைப் போலவே, ஆனால் கோப்புக்கு ஜிப் காப்பகத்தை எழுதவும்:

```bash
git archive --verbose --output=கோப்புக்கான/பாதை/கோப்பு.zip HEAD
```

- ஒரு குறிப்பிட்ட கிளையில் சமீபத்திய உறுதிப்பாட்டின் உள்ளடக்கங்களிலிருந்து தார் காப்பகத்தை உருவாக்கவும்:

```bash
git archive --output=கோப்புக்கான/பாதை/கோப்பு.tar கிளை_பெயர்
```

- ஒரு குறிப்பிட்ட கோப்பகத்தின் உள்ளடக்கங்களிலிருந்து தார் காப்பகத்தை உருவாக்கவும்:

```bash
git archive --output=கோப்புக்கான/பாதை/கோப்பு.tar HEAD:கோப்பகத்திற்கான/பாதை
```

- ஒவ்வொரு கோப்பிற்கும் ஒரு குறிப்பிட்ட கோப்பகத்திற்குள் காப்பகப்படுத்த ஒரு பாதையைத் தயாரிக்கவும்:

```bash
git archive --output=கோப்புக்கான/பாதை/கோப்பு.tar --prefix=தயார்படுத்தும்/பாதை/ HEAD
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[lincc](mailto:46962923+blueskyson@users.noreply.github.com) | *: update links via set-more-info-link.py (#7611) | 2022-01-29T21:17:39 | [b99f3da787c6](https://github.com/tldr-pages/tldr/commit/b99f3da787c6f43a545b9cb5ebd8265b1367fbc4)
[Karthikeyan Vaithilingam](mailto:seenukarthi@gmail.com) | git-archive: add Tamil translation Signed-off-by: Karthikeyan Vaithilingam <seenukarthi@gmail.com> | 2020-10-13T00:13:40 | [b12cc92ada13](https://github.com/tldr-pages/tldr/commit/b12cc92ada135969fa7baa6bfdfe3c4101c2df73)

