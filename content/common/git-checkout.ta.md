---
author: ['Karthikeyan Vaithilingam', 'lincc']
date: 1643487459
title: "git checkout"
description: "git checkout, வேலை செய்யும் மரத்திற்கு ஒரு கிளை அல்லது பாதைகளை செக்கவுட் செய்ய."
categories: "common"
---
> மேலும் விவரத்திற்கு: <https://git-scm.com/docs/git-checkout>.

- புதிய கிளையை உருவாக்கி மாறவும்:

```bash
git checkout -b கிளையின்_பெயர்
```

- ஒரு குறிப்பிட்ட குறிப்பை அடிப்படையாகக் கொண்டு புதிய கிளையை உருவாக்கி மாறவும் (கிளை, தொலை / கிளை, குறிச்சொல் சரியான குறிப்புகளின் எடுத்துக்காட்டுகள்):

```bash
git checkout -b கிளையின்_பெயர் குறிப்பு
```

- ஏற்கனவே உள்ள உள்ளூர் கிளைக்கு மாறவும்:

```bash
git checkout கிளையின்_பெயர்
```

- முன்பு செக்கவுட்ச்செய்யப்பட்ட கிளைக்கு மாறவும்:

```bash
git checkout -
```

- ஏற்கனவே உள்ள தொலை கிளைக்கு மாறவும்:

```bash
git checkout --track தொலை_பெயர்/கிளையின்_பெயர்
```

- தற்போதைய கோப்பகத்தில் நிலையற்ற அனைத்து மாற்றங்களையும் நிராகரிக்கவும் (செயல்தவிர் போன்ற கட்டளைகளுக்கு `git reset` ஐப் பார்க்கவும்):

```bash
git checkout .
```

- கொடுக்கப்பட்ட கோப்பில் நிலையற்ற மாற்றங்களை நிராகரிக்கவும்:

```bash
git checkout கோப்பு_பெயர்
```

- தற்போதைய கோப்பகத்தில் ஒரு கோப்பை ஒரு குறிப்பிட்ட கிளையில் செய்த பதிப்போடு மாற்றவும்:

```bash
git checkout கிளையின்_பெயர் -- கோப்பு_பெயர்
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[lincc](mailto:46962923+blueskyson@users.noreply.github.com) | *: update links via set-more-info-link.py (#7611) | 2022-01-29T21:17:39 | [b99f3da787c6](https://github.com/tldr-pages/tldr/commit/b99f3da787c6f43a545b9cb5ebd8265b1367fbc4)
[Karthikeyan Vaithilingam](mailto:seenukarthi@gmail.com) | git-checkout: add Tamil translation Signed-off-by: Karthikeyan Vaithilingam <seenukarthi@gmail.com> | 2020-10-13T00:13:40 | [3da34f6da523](https://github.com/tldr-pages/tldr/commit/3da34f6da523f9c931be94aa6b341a7ffa391f1d)

