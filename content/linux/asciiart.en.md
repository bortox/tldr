---
author: ['Henrique Tsuyoshi Yara', 'Sahil Dhiman']
date: 1633877152
title: "asciiart, TLDR Pages"
description: "asciiart, Convert images to ASCII."
categories: "linux"
---
> More information: <https://github.com/nodanaonlyzuul/asciiart>.

- Read an image from a file and print in ASCII:

```bash
asciiart path/to/image.jpg
```

- Read an image from a URL and print in ASCII:

```bash
asciiart www.example.com/image.jpg
```

- Choose the output width (default is 100):

```bash
asciiart --width 50 path/to/image.jpg
```

- Colorize the ASCII output:

```bash
asciiart --color path/to/image.jpg
```

- Choose the output format (default format is text):

```bash
asciiart --format text|html path/to/image.jpg
```

- Invert the character map:

```bash
asciiart --invert-chars path/to/image.jpg
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Henrique Tsuyoshi Yara](mailto:henri.tsuyoshi@hotmail.com) | asciiart: add pt_BR translation (#6917) | 2021-10-10T16:45:52 | [0b9b6f44966a](https://github.com/tldr-pages/tldr/commit/0b9b6f44966aa2ecd9f9839b073dbdbb671a5dc1)
[Sahil Dhiman](mailto:52946452+sahilister@users.noreply.github.com) | asciiart: add page (#4962) | 2020-11-21T04:07:07 | [b77cd3cc66b2](https://github.com/tldr-pages/tldr/commit/b77cd3cc66b263e9579571e2d9233dbd70fb894e)

