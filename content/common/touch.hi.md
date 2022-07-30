---
author: ['Dario Vladović', 'bl-ue', 'Abhishek Keshri', 'marchersimon']
date: 1633285326
title: "touch"
description: "touch, एक फ़ाइल का उपयोग और संशोधन समय (atime, mtime) बदलें।"
categories: "common"
---
> अधिक जानकारी: <https://www.gnu.org/software/coreutils/touch>।

- एक नई खाली फ़ाइल बनाएं (मौजूदा फ़ाइल के लिए समय बदल दें):

```bash
touch फ़ाइल का नाम
```

- फ़ाइल को किसी विशिष्ट तिथि और समय पर सेट करें:

```bash
touch -t YYYMMDDHHMM.SS फ़ाइल का नाम
```

- दूसरी फ़ाइल पर समय सेट करने के लिए फ़ाइल से समय का उपयोग करें:

```bash
touch -r पहला फ़ाइल का नाम दूसरा फ़ाइल का नाम
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | set-more-info-link.py, pages.hi/*: fix punctuation in Hindi translation (#6570) | 2021-10-03T20:22:06 | [cc25275e9687](https://github.com/tldr-pages/tldr/commit/cc25275e968713b5913477c768b61716c430d23c)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | *: clean up token syntax delimiters (#5677) | 2021-04-04T02:08:57 | [289787c7e8c1](https://github.com/tldr-pages/tldr/commit/289787c7e8c1177742d23004198253154fe50c3c)
[Dario Vladović](mailto:d.vladimyr@gmail.com) | coreutils*: use short more info links (#5658) | 2021-04-01T17:54:26 | [4830093903f6](https://github.com/tldr-pages/tldr/commit/4830093903f66ccf3ebbc2ecf477286e45edac59)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | touch: change link (#5550) | 2021-03-30T09:15:08 | [64814bb7bac0](https://github.com/tldr-pages/tldr/commit/64814bb7bac00f937c245a550a19dc2c4b62d14f)
[Abhishek Keshri](mailto:keshri.abhishek63@gmail.com) | touch: Add Hindi translation (#4456) | 2020-10-05T16:36:48 | [58c2861abe74](https://github.com/tldr-pages/tldr/commit/58c2861abe742141751da0b7b5dcbc3e63850e48)

