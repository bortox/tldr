---
author: ['Michał Gąsior']
date: 1637057745
title: "ykinfo, TLDR Pages"
description: "ykinfo, Get basic information from a YubiKey."
categories: "common"
---
> More information: <https://developers.yubico.com/yubikey-personalization/Manuals/ykinfo.1.html>.

- Display all information from YubiKey:

```bash
ykinfo -a
```

- Get only serial in decimal from YubiKey:

```bash
ykinfo -s -q
```

- Get capabilities from YubiKey:

```bash
ykinfo -c
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Michał Gąsior](mailto:rogacz@gmail.com) | ykinfo, ykman: add page (#6870) | 2021-11-16T11:15:45 | [7f0b233ea1e3](https://github.com/tldr-pages/tldr/commit/7f0b233ea1e3fe44b7c7e3186046b4da4f423b6a)

