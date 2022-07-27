---
author: ['Karthikeyan Vaithilingam', 'lincc']
date: 1643487459
title: "git bisect, TLDR Pages"
description: "git bisect, ஒரு பிழையை அறிமுகப்படுத்திய உறுதிப்பாட்டைக் கண்டுபிடிக்க பைனரி தேடலைப் பயன்படுத்தவும்."
categories: "common"
---
> தவறான உறுதிப்பாட்டை படிப்படியாகக் குறைக்க கிட் தானாகவே கமிட் வரைபடத்தில் முன்னும் பின்னுமாக குதிக்கிறது.

> மேலும் விவரத்திற்கு: <https://git-scm.com/docs/git-bisect>.

- அறியப்பட்ட தரமற்ற கமிட் மற்றும் அறியப்பட்ட சுத்தமான (பொதுவாக பழையது) வரம்புக்குட்பட்ட ஒரு கமிட் வரம்பில் ஒரு இரு அமர்வு தொடங்கவும்:

```bash
git bisect start மோசமான_கமிட் நல்ல_கமிட்
```

- `git bisect` தேர்ந்தெடுக்கும் ஒவ்வொரு உறுதிப்பாட்டிற்கும், சிக்கலுக்காக அதைச் சோதித்தபின் அதை" கெட்டது "அல்லது" நல்லது "என்று குறிக்கவும்:

```bash
git bisect good|bad
```

- `git bisect` தவறான செயலை சுட்டிக்காட்டிய பின், இருசக்கர அமர்வை முடித்துவிட்டு முந்தைய கிளைக்குத் திரும்புக:

```bash
git bisect reset
```

- ஒரு பிரிவின் போது ஒரு உறுதிப்பாட்டைத் தவிர்க்கவும் (எ.கா. வேறுபட்ட பிரச்சினை காரணமாக சோதனைகளில் தோல்வியுற்றது):

```bash
git bisect skip
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[lincc](mailto:46962923+blueskyson@users.noreply.github.com) | *: update links via set-more-info-link.py (#7611) | 2022-01-29T21:17:39 | [b99f3da787c6](https://github.com/tldr-pages/tldr/commit/b99f3da787c6f43a545b9cb5ebd8265b1367fbc4)
[Karthikeyan Vaithilingam](mailto:seenukarthi@gmail.com) | git-bisect: add Tamil translation Signed-off-by: Karthikeyan Vaithilingam <seenukarthi@gmail.com> | 2020-10-13T00:13:40 | [ba957e5c1734](https://github.com/tldr-pages/tldr/commit/ba957e5c1734a9d22de0914ee211115f2822d860)

