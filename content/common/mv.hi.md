---
author: ['Abhishek Keshri']
date: 1633515256
title: "mv, TLDR Pages"
description: "mv, फ़ाइलों और निर्देशिकाओं को स्थानांतरित या नाम बदलें।"
categories: "common"
---
> अधिक जानकारी: <https://www.gnu.org/software/coreutils/mv>।

- किसी फ़ाइल को मनमाना स्थान पर ले जाएँ:

```bash
mv स्रोत लक्ष्य
```

- फ़ाइल नाम रखते हुए फ़ाइलों को दूसरी निर्देशिका में ले जाएँ:

```bash
mv स्रोत1 स्रोत2 स्रोत3 लक्ष्य_निर्देशिका
```

- मौजूदा फाइलों को अधिलेखित करने से पहले पुष्टि के लिए संकेत न दें:

```bash
mv -f स्रोत लक्ष्य
```

- फ़ाइल अनुमतियों की परवाह किए बिना, मौजूदा फ़ाइलों को अधिलेखित करने से पहले पुष्टि के लिए संकेत दें:

```bash
mv -i स्रोत लक्ष्य
```

- लक्ष्य पर मौजूदा फाइलों को अधिलेखित न करें:

```bash
mv -n स्रोत लक्ष्य
```

- फ़ाइलों को वर्बोज़ मोड में ले जाएँ, फ़ाइलों को स्थानांतरित करने के बाद दिखाएँ:

```bash
mv -v स्रोत लक्ष्य
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Abhishek Keshri](mailto:keshri.abhishek63@gmail.com) | mv: add Hindi translation (#6736) | 2021-10-06T12:14:16 | [f0fdbd7edd15](https://github.com/tldr-pages/tldr/commit/f0fdbd7edd157115434a4f032d20a404808c1f91)

