---
author: ['Starbeamrainbowlabs']
date: 1579553918
title: "qr, TLDR Pages"
description: "qr, Generate QR codes in the terminal with ANSI VT-100 escape codes."
categories: "common"
---
> More information: <https://github.com/lincolnloop/python-qrcode/>.

- Generate a QR code:

```bash
echo "data" | qr
```

- Specify the error correction level (defaults to M):

```bash
echo "data" | qr --error-correction=L|M|Q|H
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Starbeamrainbowlabs](mailto:sbrl@starbeamrainbowlabs.com) | qr: add page (#3769) * qr: add page * Update qr.md | 2020-01-20T21:58:38 | [7916181b6ea5](https://github.com/tldr-pages/tldr/commit/7916181b6ea59c7b36631199fbd4813186882c83)

