---
author: ['Karthikeyan Vaithilingam', 'bl-ue', 'lincc']
date: 1643487459
title: "java, TLDR Pages"
description: "java, ஜாவா பயன்பாட்டு துவக்கி."
categories: "common"
---
> மேலும் விவரத்திற்கு: <https://docs.oracle.com/en/java/javase/17/docs/specs/man/java.html>.

- ஒரு main செயல்பாட்டைக் கொண்ட ஜாவா .class கோப்பை வெறும் class பெயரை பயன்படுத்தி இயக்கவும்:

```bash
java class_பெயரை
```

- ஒரு .jar நிரலை இயக்கவும்:

```bash
java -jar கோபின்_பெயர்.jar
```

- போர்ட் 5005 இல் இணைக்க காத்திருக்கும் பிழைதிருத்தி .jar நிரலை இயக்கவும்:

```bash
java -agentlib:jdwp=transport=dt_socket,server=y,suspend=y,address=*:5005 -jar கோபின்_பெயர்.jar
```

- JDK, JRE மற்றும் HotSpot மென்பொருள் பதிப்புகள் காண்பி:

```bash
java -version
```

- java கட்டளைக்கான பயன்பாட்டு தகவலை காண்பி:

```bash
java -help
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[lincc](mailto:46962923+blueskyson@users.noreply.github.com) | *: update links via set-more-info-link.py (#7611) | 2022-01-29T21:17:39 | [b99f3da787c6](https://github.com/tldr-pages/tldr/commit/b99f3da787c6f43a545b9cb5ebd8265b1367fbc4)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | multiple pages: normalize "more information" labels (#5140) | 2021-01-15T18:24:49 | [c59f12aa9f55](https://github.com/tldr-pages/tldr/commit/c59f12aa9f55d85612ba22e4da86db293ff76977)
[Karthikeyan Vaithilingam](mailto:seenukarthi@gmail.com) | java, javac: add Tamil translation (#4519) | 2020-10-07T22:06:56 | [0e3b483329fa](https://github.com/tldr-pages/tldr/commit/0e3b483329fa359b22607b16d424085937dd4438)

