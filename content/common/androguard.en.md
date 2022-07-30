---
author: ['Pierre Rudloff']
date: 1573556379
title: "androguard"
description: "androguard, Reverse engineering tool for Android applications. Written in Python."
categories: "common"
---
> More information: <https://github.com/androguard/androguard>.

- Display Android app manifest:

```bash
androguard axml path/to/app.apk
```

- Display app metadata (version and app ID):

```bash
androguard apkid path/to/app.apk
```

- Decompile Java code from an app:

```bash
androguard decompile path/to/app.apk --output path/to/directory
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Pierre Rudloff](mailto:contact@rudloff.pro) | androguard: add page (#3545) | 2019-11-12T11:59:39 | [32f696b83fb9](https://github.com/tldr-pages/tldr/commit/32f696b83fb93a1d30af5111adf353cec062c5bf)

