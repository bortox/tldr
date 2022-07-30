---
author: ['Henrique Tsuyoshi Yara']
date: 1633895935
title: "nth"
description: "nth, Name That Hash - Instantly name the type of any hash."
categories: "common"
---
> More information: <https://github.com/hashpals/name-that-hash>.

- Name a hash:

```bash
nth -t 5f4dcc3b5aa765d61d8327deb882cf99
```

- Name hashes in a file:

```bash
nth -f path/to/hashes
```

- Output in json format:

```bash
nth -t 5f4dcc3b5aa765d61d8327deb882cf99 -g
```

- Decode hash in Base64 before naming it:

```bash
nth -t NWY0ZGNjM2I1YWE3NjVkNjFkODMyN2RlYjg4MmNmOTkK -b64
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Henrique Tsuyoshi Yara](mailto:henri.tsuyoshi@hotmail.com) | nth: add page (#6853) | 2021-10-10T21:58:55 | [36977a69c8ec](https://github.com/tldr-pages/tldr/commit/36977a69c8ec64292f71ab2bd6464c3004889025)

