---
author: ['Karthikeyan Vaithilingam', 'lincc']
date: 1643487459
title: "git clean, TLDR Pages"
description: "git clean, கண்காணிக்கப்படாத கோப்புகளை பணியிடத்திலிருந்து அகற்றவும்."
categories: "common"
---
> மேலும் விவரத்திற்கு: <https://git-scm.com/docs/git-clean>.

- கிட் மூலம் கண்காணிக்கப்படாத கோப்புகளை நீக்கு:

```bash
git clean
```

- கிட் மூலம் கண்காணிக்கப்படாத கோப்புகளை ஊடாடும் வகையில் நீக்கு:

```bash
git clean -i
```

- எந்த கோப்புகள் உண்மையில் நீக்கப்படாமல் நீக்கப்படும் என்பதைக் காட்டு:

```bash
git clean --dry-run
```

- கிட் மூலம் கண்காணிக்கப்படாத கோப்புகளை கட்டாயமாக நீக்கு:

```bash
git clean -f
```

- கிட் மூலம் கண்காணிக்கப்படாத கோப்பகங்களை கட்டாயமாக நீக்கு:

```bash
git clean -fd
```

- `.gitignore` மற்றும் `.git/info/exclude` ஆகியவற்றில் புறக்கணிக்கப்பட்ட கோப்புகள் உட்பட, தடமறியப்படாத கோப்புகளை நீக்கு:

```bash
git clean -x
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[lincc](mailto:46962923+blueskyson@users.noreply.github.com) | *: update links via set-more-info-link.py (#7611) | 2022-01-29T21:17:39 | [b99f3da787c6](https://github.com/tldr-pages/tldr/commit/b99f3da787c6f43a545b9cb5ebd8265b1367fbc4)
[Karthikeyan Vaithilingam](mailto:seenukarthi@gmail.com) | git-clean: add Tamil translation Signed-off-by: Karthikeyan Vaithilingam <seenukarthi@gmail.com> | 2020-10-13T00:13:40 | [d36b54d26bf9](https://github.com/tldr-pages/tldr/commit/d36b54d26bf984099a688f497bdbffc1714b4143)

