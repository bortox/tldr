---
author: ['Peter Tripp', 'Benjamin Grant', 'lord63', 'Schneider', 'bl-ue', 'Shaun Karran', 'Marco Bonelli', 'Ruben Vereecken', '85pando', 'Jason Ge', 'Michael Utz', 'beesandbombs', 'Seth Falco', 'Starbeamrainbowlabs']
date: 1629050349
title: "convert, TLDR Pages"
description: "convert, ImageMagick image conversion tool."
categories: "common"
---
> More information: <https://imagemagick.org/script/convert.php>.

- Convert an image from JPG to PNG:

```bash
convert image.jpg image.png
```

- Scale an image 50% its original size:

```bash
convert image.png -resize 50% image2.png
```

- Scale an image keeping the original aspect ratio to a maximum dimension of 640x480:

```bash
convert image.png -resize 640x480 image2.png
```

- Horizontally append images:

```bash
convert image1.png image2.png image3.png +append image123.png
```

- Vertically append images:

```bash
convert image1.png image2.png image3.png -append image123.png
```

- Create a GIF from a series of images with 100ms delay between them:

```bash
convert image1.png image2.png image3.png -delay 10 animation.gif
```

- Create an image with nothing but a solid background:

```bash
convert -size 800x600 "xc:#ff0000" image.png
```

- Create a favicon from several images of different sizes:

```bash
convert image1.png image2.png image3.png image.ico
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Seth Falco](mailto:seth@falco.fun) | *: fix errors reported by languagetool (#6069) | 2021-08-15T19:59:09 | [3e4c519004a4](https://github.com/tldr-pages/tldr/commit/3e4c519004a471c861cdc609fd7239ee3355671c)
[Benjamin Grant](mailto:benjamin.grantGRA0007@gmail.com) | convert: add .ico example (#6143) | 2021-06-21T09:23:33 | [4232eb56cbf6](https://github.com/tldr-pages/tldr/commit/4232eb56cbf6e3646c5c85c08ba5b6c2d9b23ba5)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | *: fix typos reported by Hunspell (#5848) Co-authored-by: marchersimon <50295997+marchersimon@users.noreply.github.com> Co-authored- [...] | 2021-05-20T22:13:41 | [8ebd171d6f00](https://github.com/tldr-pages/tldr/commit/8ebd171d6f001698709fefc02b1fd5cc9f3a99c4)
[Starbeamrainbowlabs](mailto:sbrl@starbeamrainbowlabs.com) | convert: fix delay example - fixes #4064 (#4074) | 2020-06-01T21:57:34 | [05d7990bc036](https://github.com/tldr-pages/tldr/commit/05d7990bc03672625595fd13c828595a46faf1b2)
[Jason Ge](mailto:gejun_1978@yahoo.com) | convert: add vertical append example (#3581) | 2019-11-19T18:07:11 | [b777d86b57e3](https://github.com/tldr-pages/tldr/commit/b777d86b57e3d7fe556a12956d61a728af58f5e7)
[Marco Bonelli](mailto:marco@mebeim.net) | Refactor: reword English pages' links' descriptions. | 2019-06-03T14:19:41 | [66abb98ce935](https://github.com/tldr-pages/tldr/commit/66abb98ce935c0f4516bf30c4d6da72180d5a3ab)
[Schneider](mailto:lucas.schneider@sap.com) | convert.md: add homepage | 2019-04-15T01:35:17 | [64b7fedcabff](https://github.com/tldr-pages/tldr/commit/64b7fedcabfff0f50e962aa329e16cea1bdc71a0)
[Michael Utz](mailto:theutz@users.noreply.github.com) | convert: add one-liner for creating solid color images (#2863) | 2019-04-04T08:48:37 | [55edb28bab7f](https://github.com/tldr-pages/tldr/commit/55edb28bab7f20c54be973fb5498910094c9ea83)
[Shaun Karran](mailto:shaun.karran@gmail.com) | convert: add example for creating a gif (#2235) | 2018-08-08T07:27:08 | [87cf0ae9c7b3](https://github.com/tldr-pages/tldr/commit/87cf0ae9c7b33e77c47007e15753d707cdc6bad3)
[beesandbombs](mailto:dawhyte@tcd.ie) | typo | 2017-11-25T05:02:17 | [3eb2d3dcbcb7](https://github.com/tldr-pages/tldr/commit/3eb2d3dcbcb7412b4e13a6d3e29572e5496a7e8a)
[Ruben Vereecken](mailto:rubenvereecken@gmail.com) | Formatted all pages according to guidelines. | 2016-01-08T09:38:59 | [066582e8eab5](https://github.com/tldr-pages/tldr/commit/066582e8eab57bce9861cc8d379e158d61f1cc95)
[85pando](mailto:85pando@googlemail.com) | Fix another much needed imagemagick command. | 2015-12-31T11:54:03 | [a3f0d36a8050](https://github.com/tldr-pages/tldr/commit/a3f0d36a80501bcbfd38fea37fd0e196a9d980e6)
[lord63](mailto:lord63.j@gmail.com) | Fix lint for common | 2015-10-23T02:02:34 | [56a7cba6568f](https://github.com/tldr-pages/tldr/commit/56a7cba6568fcdaaeca2ddf0b80341cfc7de6285)
[Peter Tripp](mailto:petertripp@gmail.com) | Added ffmpeg, haxelib, Matt's Traceroute and imagemagick convert. | 2014-05-30T20:27:55 | [66b8ce3fc65d](https://github.com/tldr-pages/tldr/commit/66b8ce3fc65d526613a4886e49c607201d92512f)

