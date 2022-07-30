---
author: ['Dario Vladović', 'Abhishek Keshri', 'Axel Navarro', 'bl-ue', 'marchersimon']
date: 1633285326
title: "ls"
description: "ls, निर्देशिका सामग्री को सूचीबद्ध करें।"
categories: "common"
---
> अधिक जानकारी: <https://www.gnu.org/software/coreutils/ls>।

- प्रति पंक्ति एक फ़ाइल की सूची बनाएं:

```bash
ls -1
```

- छिपी हुई फाइलों सहित सभी फाइलों की सूची बनाएं:

```bash
ls -a
```

- सभी फाइलों को सूचीबद्ध करें, '/' के साथ निर्देशिका नामों को समाप्त करें:

```bash
ls -F
```

- सभी फ़ाइलों की लंबी प्रारूप सूची (अनुमतियाँ, स्वामित्व, आकार और परिवर्तन तिथि):

```bash
ls -la
```

- मानव पठनीय इकाइयों (KiB, MiB, GiB) का उपयोग करके प्रदर्शित आकार के साथ लंबी प्रारूप सूची:

```bash
ls -lh
```

- आकार के अनुसार क्रमबद्ध लंबी सूची (घटते हुए):

```bash
ls -lS
```

- संशोधन की तारीख (सबसे पहले) द्वारा क्रमबद्ध सभी फाइलों की लंबी प्रारूप सूची:

```bash
ls -ltr
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | set-more-info-link.py, pages.hi/*: fix punctuation in Hindi translation (#6570) | 2021-10-03T20:22:06 | [cc25275e9687](https://github.com/tldr-pages/tldr/commit/cc25275e968713b5913477c768b61716c430d23c)
[Dario Vladović](mailto:d.vladimyr@gmail.com) | coreutils*: use short more info links (#5658) | 2021-04-01T17:54:26 | [4830093903f6](https://github.com/tldr-pages/tldr/commit/4830093903f66ccf3ebbc2ecf477286e45edac59)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | ls: add link (#5561) | 2021-03-30T09:12:42 | [a0e1beab9bd7](https://github.com/tldr-pages/tldr/commit/a0e1beab9bd704de488fefaca86d0c5e20a7a03b)
[Axel Navarro](mailto:navarroaxel@gmail.com) | ls: fix size units in example description (#5451) | 2021-03-15T20:57:50 | [8402bf0fa60e](https://github.com/tldr-pages/tldr/commit/8402bf0fa60e2e1d94b94c75aeceba8ed40fc409)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | multiple pages: ensure exactly one colon at the end of example descriptions (#5214) | 2021-02-03T17:22:44 | [d28035c980bd](https://github.com/tldr-pages/tldr/commit/d28035c980bde01b9168e76442fe564dc82ae5b7)
[Abhishek Keshri](mailto:keshri.abhishek63@gmail.com) | ls: Add Hindi translation (#4452) | 2020-10-05T16:34:40 | [c294ce1bfb02](https://github.com/tldr-pages/tldr/commit/c294ce1bfb02f5fbb7d4ca4884ba5e1137a84441)

