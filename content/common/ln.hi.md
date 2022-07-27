---
author: ['Abhishek Keshri']
date: 1633316980
title: "ln, TLDR Pages"
description: "ln, फाइलों और निर्देशिकाओं के लिंक बनाता है।"
categories: "common"
---
> अधिक जानकारी: <https://www.gnu.org/software/coreutils/ln>।

- किसी फ़ाइल या निर्देशिका के लिए एक प्रतीकात्मक लिंक बनाएँ:

```bash
ln -s /फ़ाइल_या_निर्देशिका/का/पथ लिंक/का/पथ
```

- किसी भिन्न फ़ाइल को इंगित करने के लिए मौजूदा प्रतीकात्मक लिंक को अधिलेखित करें:

```bash
ln -sf /नई_फ़ाइल/का/पथ लिंक/का/पथ
```

- किसी फ़ाइल का हार्ड लिंक बनाएँ:

```bash
ln /फ़ाइल/का/पथ हार्डलिंक/का/पथ
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Abhishek Keshri](mailto:keshri.abhishek63@gmail.com) | ln: add Hindi translation (#6735) | 2021-10-04T05:09:40 | [89895fb49b1e](https://github.com/tldr-pages/tldr/commit/89895fb49b1ef084785ddbc3668997effba64c91)

