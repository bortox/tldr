---
author: ['Karthikeyan Vaithilingam', 'lincc', 'Tan A']
date: 1643487459
title: "git commit, TLDR Pages"
description: "git commit, கோப்புகளை களஞ்சியத்திற்கு கமிட்செய்ய."
categories: "common"
---
> மேலும் விவரத்திற்கு: <https://git-scm.com/docs/git-commit>.

- ஒரு செய்தியுடன் களஞ்சியத்திற்கு அரங்குக் கோப்புகளை கமிட் செய்யுங்கள்:

```bash
git commit -m "செய்தி"
```

- அனைத்து மாற்றியமைக்கப்பட்ட கோப்புகளையும் தானாக நிலைநிறுத்து, செய்தியுடன் கமிட் செய்யுங்கள்:

```bash
git commit -a -m "செய்தி"
```

- கடைசி கட்டத்தை தற்போதைய நிலை மாற்றங்களுடன் கமிட் செய்யுங்கள்:

```bash
git commit --amend
```

- குறிப்பிட்ட (ஏற்கனவே அரங்கேற்றப்பட்ட) கோப்புகளை மட்டுமே கமிட் செய்யுங்கள்:

```bash
git commit எனது/கோப்பு1க்கான/பாதை எனது/கோப்பு2க்கான/பாதை
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[lincc](mailto:46962923+blueskyson@users.noreply.github.com) | *: update links via set-more-info-link.py (#7611) | 2022-01-29T21:17:39 | [b99f3da787c6](https://github.com/tldr-pages/tldr/commit/b99f3da787c6f43a545b9cb5ebd8265b1367fbc4)
[Tan A](mailto:40173707+Yutyo@users.noreply.github.com) | git-commit: quote message argument (#5477) | 2021-03-19T13:26:51 | [d526739418e8](https://github.com/tldr-pages/tldr/commit/d526739418e89eba9a32b3b6acfe406abb9bdb50)
[Karthikeyan Vaithilingam](mailto:seenukarthi@gmail.com) | git-commit: add Tamil translation Signed-off-by: Karthikeyan Vaithilingam <seenukarthi@gmail.com> | 2020-10-13T00:13:40 | [1d638f4a68d1](https://github.com/tldr-pages/tldr/commit/1d638f4a68d128c19161e1af8a6e6474b2daa4bb)

