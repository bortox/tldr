---
author: ['Karthikeyan Vaithilingam', 'lincc']
date: 1643487459
title: "git cat-file, TLDR Pages"
description: "git cat-file, கிட் களஞ்சிய பொருள்களுக்கான உள்ளடக்கம் அல்லது வகை மற்றும் அளவு தகவல்களை வழங்கவும்."
categories: "common"
---
> மேலும் விவரத்திற்கு: <https://git-scm.com/docs/git-cat-file>.

- HEAD கமிட்டின் அளவை பைட்டுகளில் பெறுங்கள்:

```bash
git cat-file -s HEAD
```

- கொடுக்கப்பட்ட கிட் பொருளின் வகையை (குமிழ், மரம், கமிட், டேக்) பெறுங்கள்:

```bash
git cat-file -t 8c442dc3
```

- கொடுக்கப்பட்ட கிட் பொருளின் உள்ளடக்கத்தை அதன் வகையின் அடிப்படையில் அழகாக அச்சிடுக:

```bash
git cat-file -p HEAD~2
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[lincc](mailto:46962923+blueskyson@users.noreply.github.com) | *: update links via set-more-info-link.py (#7611) | 2022-01-29T21:17:39 | [b99f3da787c6](https://github.com/tldr-pages/tldr/commit/b99f3da787c6f43a545b9cb5ebd8265b1367fbc4)
[Karthikeyan Vaithilingam](mailto:seenukarthi@gmail.com) | git-cat-file: add Tamil translation Signed-off-by: Karthikeyan Vaithilingam <seenukarthi@gmail.com> | 2020-10-13T00:13:40 | [92b4569557ef](https://github.com/tldr-pages/tldr/commit/92b4569557efdb49200c3104f81a3d3073a3406f)

