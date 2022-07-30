---
author: ['Starbeamrainbowlabs', 'Hayden Schiff', 'pxgamer', 'Seth Falco']
date: 1629050349
title: "optipng"
description: "optipng, PNG file optimization utility."
categories: "common"
---
> More information: <http://optipng.sourceforge.net>.

- Compress a PNG with default settings:

```bash
optipng path/to/file.png
```

- Compress a PNG with the best compression:

```bash
optipng -o7 path/to/file.png
```

- Compress a PNG with the fastest compression:

```bash
optipng -o0 path/to/file.png
```

- Compress a PNG and add interlacing:

```bash
optipng -i 1 path/to/file.png
```

- Compress a PNG and preserve all metadata (including file timestamps):

```bash
optipng -preserve path/to/file.png
```

- Compress a PNG and remove all metadata:

```bash
optipng -strip all path/to/file.png
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Seth Falco](mailto:seth@falco.fun) | *: fix errors reported by languagetool (#6069) | 2021-08-15T19:59:09 | [3e4c519004a4](https://github.com/tldr-pages/tldr/commit/3e4c519004a471c861cdc609fd7239ee3355671c)
[pxgamer](mailto:owzie123@gmail.com) | optipng: add link to homepage | 2019-06-04T21:29:40 | [c49a59e8a3a6](https://github.com/tldr-pages/tldr/commit/c49a59e8a3a6cf2fde3be29cd0ad8f792630c349)
[Starbeamrainbowlabs](mailto:sbrl@starbeamrainbowlabs.com) | optipng: add preservation option (#2206) | 2018-07-21T06:27:29 | [deece664b1b4](https://github.com/tldr-pages/tldr/commit/deece664b1b4bd55bff20a826985513fb523cc23)
[Hayden Schiff](mailto:oxguy3@gmail.com) | optipng: reworded options 2 and 3 | 2016-01-28T22:07:49 | [78eebef66bb4](https://github.com/tldr-pages/tldr/commit/78eebef66bb404c85ecff61abca31e57d0035514)
[Hayden Schiff](mailto:oxguy3@gmail.com) | optipng: add page | 2016-01-28T21:47:13 | [f142b9966f27](https://github.com/tldr-pages/tldr/commit/f142b9966f27b0b039c97be217d434205f58e3da)

