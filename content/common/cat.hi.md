---
author: ['Dario Vladović', 'Atharv Phadnis', 'marchersimon']
date: 1633285326
title: "cat"
description: "cat, फ़ाइलों को प्रिंट और संक्षिप्त करें।"
categories: "common"
---
> अधिक जानकारी: <https://www.gnu.org/software/coreutils/cat>।

- मानक आउटपुट में फ़ाइल की सामग्री प्रिंट करें:

```bash
cat फ़ाइल
```

- लक्ष्य फ़ाइल में कई फ़ाइलों को संयुक्त करें:

```bash
cat फ़ाइल1 फ़ाइल2 > लक्ष्य_फ़ाइल
```

- लक्ष्य फ़ाइल के अंत में कई फ़ाइलें संलग्न करें:

```bash
cat फ़ाइल1 फ़ाइल2 >> लक्ष्य_फ़ाइल
```

- सभी आउटपुट लाइनों की संख्या:

```bash
cat -n फ़ाइल
```

- गैर-मुद्रण योग्य और सफेदस्थान पात्र प्रदर्शित करें (M-उपसर्ग के साथ यदि गैर-ASCII):

```bash
cat -v -t -e फ़ाइल
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | set-more-info-link.py, pages.hi/*: fix punctuation in Hindi translation (#6570) | 2021-10-03T20:22:06 | [cc25275e9687](https://github.com/tldr-pages/tldr/commit/cc25275e968713b5913477c768b61716c430d23c)
[Dario Vladović](mailto:d.vladimyr@gmail.com) | coreutils*: use short more info links (#5658) | 2021-04-01T17:54:26 | [4830093903f6](https://github.com/tldr-pages/tldr/commit/4830093903f66ccf3ebbc2ecf477286e45edac59)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | cat: change more information link (#5551) | 2021-03-30T12:31:55 | [3d97ba7785c1](https://github.com/tldr-pages/tldr/commit/3d97ba7785c175e55c9c9ac06f1f20b08837ea5d)
[Atharv Phadnis](mailto:31766648+Athi223@users.noreply.github.com) | cat, chsh, false, git-init, time, view: add Hindi translations (#4598) | 2020-10-12T23:01:55 | [323e9c0b46b8](https://github.com/tldr-pages/tldr/commit/323e9c0b46b8453f630e1f533d526f900c7cc6cc)

