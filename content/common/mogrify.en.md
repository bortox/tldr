---
author: ['Waldir Pimenta', 'Marco Bonelli', 'pxgamer', 'wefhy', 'Seth Falco']
date: 1629050349
title: "mogrify"
description: "mogrify, Perform operations on multiple images, such as resizing, cropping, flipping, and adding effects."
categories: "common"
---
> Changes are applied directly to the original file.

> More information: <https://imagemagick.org/script/mogrify.php>.

- Resize all JPEG images in the directory to 50% of their initial size:

```bash
mogrify -resize 50% *.jpg
```

- Resize all images starting with "DSC" to 800x600:

```bash
mogrify -resize 800x600 DSC*
```

- Convert all PNGs in the directory to JPEG:

```bash
mogrify -format jpg *.png
```

- Halve the saturation of all image files in the current directory:

```bash
mogrify -modulate 100,50 *
```

- Double the brightness of all image files in the current directory:

```bash
mogrify -modulate 200 *
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Seth Falco](mailto:seth@falco.fun) | *: fix errors reported by languagetool (#6069) | 2021-08-15T19:59:09 | [3e4c519004a4](https://github.com/tldr-pages/tldr/commit/3e4c519004a471c861cdc609fd7239ee3355671c)
[pxgamer](mailto:owzie123@gmail.com) | mogrify: add link to homepage | 2019-06-04T21:29:40 | [a138ead5be11](https://github.com/tldr-pages/tldr/commit/a138ead5be1126cc6cb7f046fbbe8c42c8b77654)
[Marco Bonelli](mailto:mb5.marcob@gmail.com) | Refactor: change "folder" to "directory" where needed. This commit fixes every instance in which the word "folder" is incorrectly used [...] | 2019-02-13T16:21:04 | [2599a6de483a](https://github.com/tldr-pages/tldr/commit/2599a6de483a70601ab17b29e0f18a5a8bdcaa12)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | changes per PR review / capitalization of acronyms | 2017-09-17T07:22:39 | [cd31c6947974](https://github.com/tldr-pages/tldr/commit/cd31c694797406eaf24bf8e3d139d715084ff048)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | mogrify: tweak descriptions | 2017-09-17T07:22:39 | [924c28cb24a8](https://github.com/tldr-pages/tldr/commit/924c28cb24a838f02cf893524f75b822577cc01d)
[wefhy](mailto:wefhy007@gmail.com) | mogrify: add page (#1447) | 2017-08-20T19:37:03 | [024b2107ae10](https://github.com/tldr-pages/tldr/commit/024b2107ae10a1979d872fdfee1ecaca05291835)

