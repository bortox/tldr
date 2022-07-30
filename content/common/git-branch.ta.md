---
author: ['Karthikeyan Vaithilingam', 'lincc']
date: 1643487459
title: "git branch"
description: "git branch, கிளைகளுடன் வேலை செய்வதற்கான பிரதான கிட் கட்டளை."
categories: "common"
---
> மேலும் விவரத்திற்கு: <https://git-scm.com/docs/git-branch>.

- கணினியில் உள்ள அனைத்து கிளைகளையும் பட்டியலிடுங்கள். தற்போதைய கிளை `*` ஆல் சிறப்பிக்கப்படுகிறது:

```bash
git branch
```

- அனைத்து கிளைகளையும் பட்டியலிடுங்கள் (கணினி மற்றும் தொலை களஞ்சியங்களில்):

```bash
git branch -a
```

- தற்போதைய கிளையின் பெயரைக் காட்டு:

```bash
git branch --show-current
```

- தற்போதைய கமிட்டின் அடிப்படையில் புதிய கிளையை உருவாக்கவும்:

```bash
git branch கிளையின்_பெயர்
```

- ஒரு குறிப்பிட்ட கமிட்டின் அடிப்படையில் புதிய கிளையை உருவாக்கவும்:

```bash
git branch கிளையின்_பெயர் கமிட்_ஹாஷ்
```

- ஒரு கிளையின் மறுபெயரிடு (இதை செய்ய அந்த கிளையை செக்கவுட் செய்த்திருக்க கூடாது):

```bash
git branch -m பழைய_கிளையின்_பெயர் புதிய_கிளையின்_பெயர்
```

- கணினியில் ஒரு கிளையை நீக்கு (இதை செய்ய அந்த கிளையை செக்கவுட் செய்த்திருக்க கூடாது):

```bash
git branch -d கிளையின்_பெயர்
```

- தொலை களஞ்சியத்தில் ஒரு கிளையை நீக்கு:

```bash
git push தொலை_களஞ்சிய_பெயர் --delete தொலை_கிளையின்_பெயர்
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[lincc](mailto:46962923+blueskyson@users.noreply.github.com) | *: update links via set-more-info-link.py (#7611) | 2022-01-29T21:17:39 | [b99f3da787c6](https://github.com/tldr-pages/tldr/commit/b99f3da787c6f43a545b9cb5ebd8265b1367fbc4)
[Karthikeyan Vaithilingam](mailto:seenukarthi@gmail.com) | git-branch: add Tamil translation Signed-off-by: Karthikeyan Vaithilingam <seenukarthi@gmail.com> | 2020-10-13T00:13:40 | [256ae8a0cd4b](https://github.com/tldr-pages/tldr/commit/256ae8a0cd4b2940d1f14670c8525ca2297f3d7a)

