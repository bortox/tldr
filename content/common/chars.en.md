---
author: ['David']
date: 1572381138
title: "chars, TLDR Pages"
description: "chars, Display names and codes for various ASCII and Unicode characters and code points."
categories: "common"
---
> More information: <https://github.com/antifuchs/chars>.

- Look up a character by its value:

```bash
chars 'ß'
```

- Look up a character by its Unicode code point:

```bash
chars U+1F63C
```

- Look up possible characters given an ambiguous code point:

```bash
chars 10
```

- Look up a control character:

```bash
chars "^C"
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[David](mailto:animi.vulpis@gmail.com) | chars: add page (#3489) | 2019-10-29T21:32:18 | [48e16bc381a8](https://github.com/tldr-pages/tldr/commit/48e16bc381a87d5151350cbfc0086706e76f4770)

