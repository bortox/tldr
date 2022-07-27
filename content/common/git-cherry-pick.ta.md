---
author: ['Karthikeyan Vaithilingam', 'lincc']
date: 1643487459
title: "git cherry-pick, TLDR Pages"
description: "git cherry-pick, தற்போதுள்ள கமிட்டுகளால் அறிமுகப்படுத்தப்பட்ட மாற்றங்களை தற்போதைய கிளையில் பயன்படுத்துங்கள்."
categories: "common"
---
> மற்றொரு கிளையில் மாற்றங்களைப் பயன்படுத்த, முதலில் விரும்பிய கிளைக்கு மாற `git checkout` ஐப் பயன்படுத்தவும்.

> மேலும் விவரத்திற்கு: <https://git-scm.com/docs/git-cherry-pick>.

- தற்போதைய கிளைக்கு ஒரு கமிட்டை பயன்படுத்துங்கள்:

```bash
git cherry-pick கமிட்
```

- தற்போதைய கிளையில் பலவிதமான கமிட்டுகளைப் பயன்படுத்துங்கள் (மேலும் `git rebase --onto` பார்க்கவும் ):

```bash
git cherry-pick தொடக்க_கமிட்~..முடிவு_கமிட்
```

- தற்போதைய கிளைக்கு பல (வரிசை அல்லாத) கமிட்டுகளைப் பயன்படுத்துங்கள்:

```bash
git cherry-pick கமிட்_1 கமிட்_2
```

- ஒரு கமிட்டை உருவாக்காமல், பணிபுரியும் கோப்பகத்தில் ஒரு கமிட்டின் மாற்றங்களைச் சேர்க்கவும்:

```bash
git cherry-pick -n கமிட்
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[lincc](mailto:46962923+blueskyson@users.noreply.github.com) | *: update links via set-more-info-link.py (#7611) | 2022-01-29T21:17:39 | [b99f3da787c6](https://github.com/tldr-pages/tldr/commit/b99f3da787c6f43a545b9cb5ebd8265b1367fbc4)
[Karthikeyan Vaithilingam](mailto:seenukarthi@gmail.com) | git-cherry-pick: add Tamil translation Signed-off-by: Karthikeyan Vaithilingam <seenukarthi@gmail.com> | 2020-10-13T00:13:40 | [717a1aeb579e](https://github.com/tldr-pages/tldr/commit/717a1aeb579e73a7156245e972fea9d01f9f3b52)

