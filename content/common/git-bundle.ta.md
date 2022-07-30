---
author: ['Karthikeyan Vaithilingam', 'lincc']
date: 1643487459
title: "git bundle"
description: "git bundle, ஒரு காப்பக கோப்பில் பொருள்கள் மற்றும் குறிப்புகளை தொகுக்கவும்."
categories: "common"
---
> மேலும் விவரத்திற்கு: <https://git-scm.com/docs/git-bundle>.

- ஒரு குறிப்பிட்ட கிளையின் அனைத்து பொருள்கள் மற்றும் குறிப்புகளைக் கொண்ட ஒரு மூட்டை கோப்பை உருவாக்கவும்:

```bash
git bundle create கோப்புக்கான/பாதை/கோப்பு.bundle கிளையின்_பெயர்
```

- அனைத்து கிளைகளின் மூட்டை கோப்பை உருவாக்கவும்:

```bash
git bundle create கோப்புக்கான/பாதை/கோப்பு.bundle --all
```

- தற்போதைய கிளையின் கடைசி 5 கமிட்டுகளின் மூட்டை கோப்பை உருவாக்கவும்:

```bash
git bundle create கோப்புக்கான/பாதை/கோப்பு.bundle -5 HEAD
```

- சமீபத்திய 7 நாட்களின் மூட்டை கோப்பை உருவாக்கவும்:

```bash
git bundle create கோப்புக்கான/பாதை/கோப்பு.bundle --since=7.days HEAD
```

- ஒரு மூட்டை கோப்பு தற்போதைய களஞ்சியத்தில் செல்லுபடியாகும் மற்றும் பயன்படுத்தலாம் என்பதை சரிபார்க்கவும்:

```bash
git bundle verify கோப்புக்கான/பாதை/கோப்பு.bundle
```

- ஒரு மூட்டையில் உள்ள குறிப்புகளின் பட்டியலை நிலையான வெளியீட்டில் அச்சிடுக:

```bash
git bundle unbundle கோப்புக்கான/பாதை/கோப்பு.bundle
```

- ஒரு மூட்டை கோப்பிலிருந்து ஒரு குறிப்பிட்ட கிளையை தற்போதைய களஞ்சியத்தில் இணைக்கவும்:

```bash
git pull கோப்புக்கான/பாதை/கோப்பு.bundle கிளையின்_பெயர்
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[lincc](mailto:46962923+blueskyson@users.noreply.github.com) | *: update links via set-more-info-link.py (#7611) | 2022-01-29T21:17:39 | [b99f3da787c6](https://github.com/tldr-pages/tldr/commit/b99f3da787c6f43a545b9cb5ebd8265b1367fbc4)
[Karthikeyan Vaithilingam](mailto:seenukarthi@gmail.com) | git-bundle: add Tamil translation Signed-off-by: Karthikeyan Vaithilingam <seenukarthi@gmail.com> | 2020-10-13T00:13:40 | [304cdd426476](https://github.com/tldr-pages/tldr/commit/304cdd4264768f205109a596c96cc800dae5728e)

