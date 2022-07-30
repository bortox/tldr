---
author: ['Karthikeyan Vaithilingam', 'Lucas Gabriel Schneider', 'lincc']
date: 1643487459
title: "git check-ignore"
description: "git check-ignore, ('.gitignore') கோப்புகளை புறக்கணிக்கவும் / விலக்கவும் பகுப்பாய்வு செய்து பிழைத்திருத்தம் செய்யுங்கள்."
categories: "common"
---
> மேலும் விவரத்திற்கு: <https://git-scm.com/docs/git-check-ignore>.

- ஒரு கோப்பு அல்லது கோப்புறை புறக்கணிக்கப்பட்டுள்ளதா என சரிபார்க்கவும்:

```bash
git check-ignore கோப்பு_அல்லது_கோப்புறைக்கான/பாதை
```

- பல கோப்புகள் அல்லது கோப்பகங்கள் புறக்கணிக்கப்படுகின்றனவா என்பதைச் சரிபார்க்கவும்:

```bash
git check-ignore கோப்புக்கான_பாதை கோப்புறைக்கான_பாதை
```

- stdin இலிருந்து ஒரு வரியில் ஒன்றுக்கு பாதை பெயர்களைப் பயன்படுத்தவும்:

```bash
git check-ignore --stdin < கோப்பு_பட்டியலுக்கான/பாதை
```

- குறியீட்டை சரிபார்க்க வேண்டாம் (பாதைகள் ஏன் கண்காணிக்கப்பட்டன மற்றும் புறக்கணிக்கப்படவில்லை என்பதை பிழைத்திருத்த பயன்படுகிறது):

```bash
git check-ignore --no-index கோப்புகள்_அல்லது_கோப்புறைகளுக்கான/பாதை
```

- ஒவ்வொரு பாதைக்கும் பொருந்தும் முறை பற்றிய விவரங்களைச் சேர்க்கவும்:

```bash
git check-ignore --verbose கோப்புகள்_அல்லது_கோப்புறைகளுக்கான/பாதை
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[lincc](mailto:46962923+blueskyson@users.noreply.github.com) | *: update links via set-more-info-link.py (#7611) | 2022-01-29T21:17:39 | [b99f3da787c6](https://github.com/tldr-pages/tldr/commit/b99f3da787c6f43a545b9cb5ebd8265b1367fbc4)
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | multiple pages: format technical tokens (#5119) Co-authored-by: bl-ue <54780737+bl-ue@users.noreply.github.com> Co-authored-by: [...] | 2021-01-31T18:05:18 | [a5fe31bc47ae](https://github.com/tldr-pages/tldr/commit/a5fe31bc47aece3efa5e66b52b3cf384f27d5d72)
[Karthikeyan Vaithilingam](mailto:seenukarthi@gmail.com) | git-check-ignore: add Tamil translation Signed-off-by: Karthikeyan Vaithilingam <seenukarthi@gmail.com> | 2020-10-13T00:13:40 | [1d4d0b0ffdb6](https://github.com/tldr-pages/tldr/commit/1d4d0b0ffdb674138f6d7bf4b32cc97d955f8595)

