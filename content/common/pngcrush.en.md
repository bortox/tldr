---
author: ['pxgamer', 'Leandro Ostera', 'Seth Falco', 'Hayden Schiff']
date: 1629050349
title: "pngcrush, TLDR Pages"
description: "pngcrush, PNG compression utility."
categories: "common"
---
> More information: <https://pmt.sourceforge.io/pngcrush>.

- Compress a PNG file:

```bash
pngcrush in.png out.png
```

- Compress all PNGs and output them to the specified directory:

```bash
pngcrush -d path/to/output *.png
```

- Compress PNG file with all 114 available algorithms and pick the best result:

```bash
pngcrush -rem allb -brute -reduce in.png out.png
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Seth Falco](mailto:seth@falco.fun) | *: fix errors reported by languagetool (#6069) | 2021-08-15T19:59:09 | [3e4c519004a4](https://github.com/tldr-pages/tldr/commit/3e4c519004a471c861cdc609fd7239ee3355671c)
[pxgamer](mailto:owzie123@gmail.com) | pngcrush: add link to homepage | 2019-05-31T20:47:40 | [a8deffff0aee](https://github.com/tldr-pages/tldr/commit/a8deffff0aeeffd53919e551e091be954805b25f)
[Leandro Ostera](mailto:leandro@ostera.io) | Fixes -brute description | 2016-02-08T14:05:52 | [682a55a781c3](https://github.com/tldr-pages/tldr/commit/682a55a781c3ab2c39104843ae86f0963596102f)
[Hayden Schiff](mailto:oxguy3@gmail.com) | pngcrush: changed wording to match optipng | 2016-01-28T22:27:44 | [5d671ea9659b](https://github.com/tldr-pages/tldr/commit/5d671ea9659ba3a997f7f4e6fee0ce9c752f1222)
[Hayden Schiff](mailto:oxguy3@gmail.com) | pngcrush: add page | 2016-01-28T21:44:45 | [c2f3ce125bae](https://github.com/tldr-pages/tldr/commit/c2f3ce125baed79afb64f9bb8ab22e7985a81377)

