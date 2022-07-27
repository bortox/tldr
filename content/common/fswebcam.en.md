---
author: ['lord63', 'Ruben Vereecken', 'pxgamer', 'Like-all', 'Artem Buslov', 'Lucas Gabriel Schneider']
date: 1612112718
title: "fswebcam, TLDR Pages"
description: "fswebcam, Small and simple webcam for *nix."
categories: "common"
---
> More information: <https://www.sanslogic.co.uk/fswebcam>.

- Take a picture:

```bash
fswebcam filename
```

- Take a picture with custom resolution:

```bash
fswebcam -r widthxheight filename
```

- Take a picture from selected device(Default is `/dev/video0`):

```bash
fswebcam -d device filename
```

- Take a picture with timestamp(timestamp string is formatted by strftime):

```bash
fswebcam --timestamp timestamp filename
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | multiple pages: format technical tokens (#5119) Co-authored-by: bl-ue <54780737+bl-ue@users.noreply.github.com> Co-authored-by: [...] | 2021-01-31T18:05:18 | [a5fe31bc47ae](https://github.com/tldr-pages/tldr/commit/a5fe31bc47aece3efa5e66b52b3cf384f27d5d72)
[pxgamer](mailto:owzie123@gmail.com) | fswebcam: add link to homepage | 2019-06-07T23:58:59 | [3a4b8fec8f76](https://github.com/tldr-pages/tldr/commit/3a4b8fec8f7604b5bca927f2ba15e23e678ee9cb)
[Artem Buslov](mailto:buslov.artem@gmail.com) | fswebcam: fix typo in device name (#1837) | 2017-12-24T21:50:33 | [2bed8e86bd6d](https://github.com/tldr-pages/tldr/commit/2bed8e86bd6de0053339729cda30e1348757391f)
[Ruben Vereecken](mailto:rubenvereecken@gmail.com) | Formatted all pages according to guidelines. | 2016-01-08T09:38:59 | [066582e8eab5](https://github.com/tldr-pages/tldr/commit/066582e8eab57bce9861cc8d379e158d61f1cc95)
[lord63](mailto:lord63.j@gmail.com) | Fix lint for common | 2015-10-23T02:02:34 | [56a7cba6568f](https://github.com/tldr-pages/tldr/commit/56a7cba6568fcdaaeca2ddf0b80341cfc7de6285)
[Like-all](mailto:like-all@yandex.com) | webcam utils | 2014-09-12T12:56:18 | [f48efad4de95](https://github.com/tldr-pages/tldr/commit/f48efad4de9506aecec49c948d31b6cd502c6e07)

