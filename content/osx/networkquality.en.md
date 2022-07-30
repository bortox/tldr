---
author: ['Muhammad Falak R Wani']
date: 1637411177
title: "networkQuality"
description: "networkQuality, Measure the network quality by connecting to the internet."
categories: "osx"
---
> More information: <https://support.apple.com/HT212313>.

- Test the network quality for the default interface:

```bash
networkQuality
```

- Test the upload and download speeds sequentially instead of in parallel:

```bash
networkQuality -s
```

- Test a specified network interface:

```bash
networkQuality -I en0
```

- Test the network quality with verbose output:

```bash
networkQuality -v
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Muhammad Falak R Wani](mailto:falakreyaz@gmail.com) | networkquality: add page (#7444) | 2021-11-20T13:26:17 | [bee87ee2b5fa](https://github.com/tldr-pages/tldr/commit/bee87ee2b5fab5ca35ece89d972e01048d4a1f28)

