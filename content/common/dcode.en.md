---
author: ['bl-ue']
date: 1618386190
title: "dcode, TLDR Pages"
description: "dcode, Recursively detect and decode strings, supporting hex, decimal, binary, base64, URL, FromChar encodings, Caesar ciphers, and MD5, SHA1, and SHA2 hashes."
categories: "common"
---
> Warning: uses 3rd-party web services for MD5, SHA1 and SHA2 hash lookups. For sensitive data, use `-s` to avoid these services.

> More information: <https://github.com/s0md3v/Decodify>.

- Recursively detect and decode a string:

```bash
dcode "NjM3YTQyNzQ1YTQ0NGUzMg=="
```

- Rotate a string by the specified offset:

```bash
dcode -rot 11 "spwwz hzcwo"
```

- Rotate a string by all 26 possible offsets:

```bash
dcode -rot all "bpgkta xh qtiitg iwpc sr"
```

- Reverse a string:

```bash
dcode -rev "hello world"
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | dcode: add page (#5747) | 2021-04-14T09:43:10 | [50834bafd7c3](https://github.com/tldr-pages/tldr/commit/50834bafd7c3108120319ac476bc6253a7b7e49c)

