---
author: ['Pierre Rudloff']
date: 1573598633
title: "zipalign, TLDR Pages"
description: "zipalign, Zip archive alignment tool."
categories: "common"
---
> Part of the Android SDK build tools.

> More information: <https://developer.android.com/studio/command-line/zipalign>.

- Align the data of a ZIP file on 4-byte boundaries:

```bash
zipalign 4 path/to/input.zip path/to/output.zip
```

- Check that a ZIP file is correctly aligned on 4-byte boundaries and display the results in a verbose manner:

```bash
zipalign -v -c 4 path/to/input.zip
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Pierre Rudloff](mailto:contact@rudloff.pro) | zipalign: add page (#3546) Thanks for the page @Rudloff! | 2019-11-12T23:43:53 | [af6a4e9dbcca](https://github.com/tldr-pages/tldr/commit/af6a4e9dbccafe54448a19d756115e646b8a97a4)

