---
author: ['Sailesh Shrestha', 'Seth Falco', 'lincc']
date: 1648358715
title: "alias, TLDR Pages"
description: "alias, उपनामहरु बनाउछ -- सब्दहरु जसले आदेश स्टृङ्लाइ प्रतिस्थापन् गर्छ।"
categories: "common"
---
> शेलको कन्फिगुरेतिओन् फाइलमा (जस्तै `~/.bashrc`) परिभासित् नगरेको खन्डमा उपनामहरुको आयु चलिरहेको शेल् सेसन् सङै सकिन्छ।

> थप जानकारी: <https://tldp.org/LDP/abs/html/aliases.html>.

- सबै उपनामहरुको सुची बनाउनुहोस्:

```bash
alias
```

- एउटा सामान्य उपनाम बनाउनुहोस्:

```bash
alias  शब्द="आदेश"
```

- एउटा आदेशसङ्ग सम्बन्धित उपनाम हेर्नुहोस्:

```bash
alias शब्द
```

- उपनाम बनाइएको आदेशलाई हटाउनुहोस्:

```bash
unalias शब्द
```

- `rm` लाई एउटा अन्तरकृयात्मक आदेशमा बदल्नुहोस्:

```bash
alias rm="rm -i"
```

- `la` लाई `ls -a` को सर्ट्कट् बनाउनुहोस्:

```bash
alias la="ls -a"
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Seth Falco](mailto:seth@falco.fun) | *: normalize colons (#7913) | 2022-03-27T07:25:15 | [27ff55fc2eea](https://github.com/tldr-pages/tldr/commit/27ff55fc2eea445eb5216c3b1d934960539fc024)
[lincc](mailto:46962923+blueskyson@users.noreply.github.com) | *: update links via set-more-info-link.py (#7611) | 2022-01-29T21:17:39 | [b99f3da787c6](https://github.com/tldr-pages/tldr/commit/b99f3da787c6f43a545b9cb5ebd8265b1367fbc4)
[Sailesh Shrestha](mailto:34860977+werewolf-65@users.noreply.github.com) | alias, at: add Nepali translation (#7221) | 2021-10-29T15:57:49 | [1c0222ee731a](https://github.com/tldr-pages/tldr/commit/1c0222ee731a4ac7fcdd3b139c6c234324609e2e)

