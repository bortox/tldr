---
author: ['Karthikeyan Vaithilingam', 'lincc']
date: 1643487459
title: "git add"
description: "git add, மாற்றப்பட்ட கோப்புகளை குறியீட்டில் சேர்க்கிறது."
categories: "common"
---
> மேலும் விவரத்திற்கு: <https://git-scm.com/docs/git-add>.

- குறியீட்டில் ஒரு கோப்பைச் சேர்க்க:

```bash
git add கோப்புக்கான/பாதை
```

- எல்லா கோப்புகளையும் சேர்க்கவும் (கண்காணிக்கப்பட்ட மற்றும் தடமறியப்படாத):

```bash
git add -A
```

- ஏற்கனவே கண்காணிக்கப்பட்ட கோப்புகளை மட்டுமே சேர்க்கவும்:

```bash
git add -u
```

- புறக்கணிக்கப்பட்ட கோப்புகளையும் சேர்க்கவும்:

```bash
git add -f
```

- ஊடாடும் வகையில் சில கோப்புகளை சேர்க்கவும்:

```bash
git add -p
```

- கொடுக்கப்பட்ட கோப்பின் ஊடாடும் கட்ட பாகங்கள் சேர்க்கவும்:

```bash
git add -p கோப்புக்கான/பாதை
```

- ஒரு கோப்பை ஊடாடும் வகையில் சேர்க்கவும்:

```bash
git add -i
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[lincc](mailto:46962923+blueskyson@users.noreply.github.com) | *: update links via set-more-info-link.py (#7611) | 2022-01-29T21:17:39 | [b99f3da787c6](https://github.com/tldr-pages/tldr/commit/b99f3da787c6f43a545b9cb5ebd8265b1367fbc4)
[Karthikeyan Vaithilingam](mailto:seenukarthi@gmail.com) | git-add: add Tamil translation Signed-off-by: Karthikeyan Vaithilingam <seenukarthi@gmail.com> | 2020-10-13T00:13:40 | [24a53702fb02](https://github.com/tldr-pages/tldr/commit/24a53702fb029b645239e894887cefcc7980cbc7)

