---
author: ['Karthikeyan Vaithilingam', 'Lucas Gabriel Schneider', 'lincc']
date: 1643487459
title: "javac"
description: "javac, ஜாவா நிரல்மொழிமாற்றி."
categories: "common"
---
> மேலும் விவரத்திற்கு: <https://docs.oracle.com/en/java/javase/17/docs/specs/man/javac.html>.

- `.java` கோப்பை நிரல்மொழிமாற்ற:

```bash
javac கோப்பு.java
```

- பல `.java` கோப்புகளை நிரல்மொழிமாற்ற:

```bash
javac கோப்பு1.java கோப்பு2.java கோப்பு3.java
```

- தற்போதைய கோப்பகத்தில் அனைத்து `.java` கோப்புகளையும் நிரல்மொழிமாற்ற:

```bash
javac *.java
```

- ஒரு `.java` கோப்பை நிரல்மொழிமாற்றி, அதன் விளைவாக வரும் `.class` கோப்பை ஒரு குறிப்பிட்ட கோப்பகத்தில் வைக்கவும்:

```bash
javac -d கோப்புறையை/குறிவைக்கும்/பாதை கோப்பு.java
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[lincc](mailto:46962923+blueskyson@users.noreply.github.com) | *: update links via set-more-info-link.py (#7611) | 2022-01-29T21:17:39 | [b99f3da787c6](https://github.com/tldr-pages/tldr/commit/b99f3da787c6f43a545b9cb5ebd8265b1367fbc4)
[lincc](mailto:46962923+blueskyson@users.noreply.github.com) | exec, javac: add more information link (#6536) | 2021-09-16T20:50:00 | [53bb0828896b](https://github.com/tldr-pages/tldr/commit/53bb0828896bfcca7b5ce118fe241ef20c7a6fb0)
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | multiple pages: format technical tokens (#5119) Co-authored-by: bl-ue <54780737+bl-ue@users.noreply.github.com> Co-authored-by: [...] | 2021-01-31T18:05:18 | [a5fe31bc47ae](https://github.com/tldr-pages/tldr/commit/a5fe31bc47aece3efa5e66b52b3cf384f27d5d72)
[Karthikeyan Vaithilingam](mailto:seenukarthi@gmail.com) | java, javac: add Tamil translation (#4519) | 2020-10-07T22:06:56 | [0e3b483329fa](https://github.com/tldr-pages/tldr/commit/0e3b483329fa359b22607b16d424085937dd4438)

