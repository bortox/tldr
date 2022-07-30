---
author: ['Abhishek Keshri']
date: 1633296062
title: "alias"
description: "alias, उपनाम बनाता है -- ऐसे शब्द जिन्हें कमांड स्ट्रिंग द्वारा प्रतिस्थापित किया जाता है।"
categories: "common"
---
> उपनाम वर्तमान शेल सत्र के साथ समाप्त हो जाता है जब तक कि शेल की कॉन्फ़िगरेशन फ़ाइल में परिभाषित नहीं किया जाता है, उदा। `~/.bashrc`।

> अधिक जानकारी: <https://tldp.org/LDP/abs/html/aliases.html>।

- सभी उपनामों की सूची बनाएं:

```bash
alias
```

- एक सामान्य उपनाम बनाएं:

```bash
alias शब्द="आदेश"
```

- किसी दिए गए उपनाम से जुड़ी कमांड देखें:

```bash
alias शब्द
```

- एक अलियास कमांड निकालें:

```bash
unalias शब्द
```

- `rm` को एक इंटरैक्टिव कमांड में बदलें:

```bash
alias rm="rm -i"
```

- `ls -a` के शॉर्टकट के रूप में `la` बनाएं:

```bash
alias la="ls -a"
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Abhishek Keshri](mailto:keshri.abhishek63@gmail.com) | alias: add Hindi translation (#6741) | 2021-10-03T23:21:02 | [6cc363d8c321](https://github.com/tldr-pages/tldr/commit/6cc363d8c321a257965c3dc7173bba8e669a7b56)

