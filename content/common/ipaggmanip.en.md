---
author: ['Juri']
date: 1634764911
title: "ipaggmanip, TLDR Pages"
description: "ipaggmanip, Manipulate aggregate statistics produced by `ipaggcreate`."
categories: "common"
---
> More information: <https://manned.org/ipaggmanip>.

- Combine labels equal in their high-order bits:

```bash
ipaggmanip --prefix 16 path/to/file
```

- Remove labels with a count smaller than a given number of bytes and output a random sample of such labels:

```bash
ipaggmanip --cut-smaller 100 --cull-labels 5 path/to/file
```

- Replace each label's count with 1 if it is non-zero:

```bash
ipaggmanip --posterize path/to/file
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Juri](mailto:juri.dispan@posteo.net) | ipsumdump, ipaggcreate, ipaggmanip: add page (#6966) | 2021-10-20T23:21:51 | [e26d7c6659fd](https://github.com/tldr-pages/tldr/commit/e26d7c6659fdd1a2ddd9dcf0d57c95eaa4615f94)

