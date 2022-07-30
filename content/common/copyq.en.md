---
author: ['Ein Verne']
date: 1571233713
title: "copyq"
description: "copyq, Clipboard manager with advanced features."
categories: "common"
---
> More information: <https://hluk.github.io/CopyQ/>.

- Launch CopyQ to store clipboard history:

```bash
copyq
```

- Show current clipboard content:

```bash
copyq clipboard
```

- Insert raw text into the clipboard history:

```bash
copyq add -- text1 text2 text3
```

- Insert text containing escape sequences ('\n', '\t') into the clipboard history:

```bash
copyq add firstline\nsecondline
```

- Print the content of the first 3 items in the clipboard history:

```bash
copyq read 0 1 2
```

- Copy a file's contents into the clipboard:

```bash
copyq copy < file.txt
```

- Copy a JPEG image into the clipboard:

```bash
copyq copy image/jpeg < image.jpg
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Ein Verne](mailto:einverne@gmail.com) | copyd: fix empty space in filename (#3429) | 2019-10-16T15:48:33 | [4582f186dd58](https://github.com/tldr-pages/tldr/commit/4582f186dd5870ca643783f293b24a1f17afd286)

