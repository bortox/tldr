---
author: ['Waldir Pimenta', 'bl-ue', 'pxgamer', 'Seth Falco', 'Starbeamrainbowlabs']
date: 1629050349
title: "montage, TLDR Pages"
description: "montage, ImageMagick image montage tool."
categories: "common"
---
> Tiles images into a customisable grid.

> More information: <https://imagemagick.org/script/montage.php>.

- Tile images into a grid, automatically resizing images larger than the grid cell size:

```bash
montage image1.png image2.jpg imageN.png montage.jpg
```

- Tile images into a grid, automatically calculating the grid cell size from the largest image:

```bash
montage image1.png image2.jpg imageN.png -geometry +0+0 montage.jpg
```

- Set the grid cell size and resize images to fit it before tiling:

```bash
montage image1.png image2.jpg imageN.png -geometry 640x480+0+0 montage.jpg
```

- Limit the number of rows and columns in the grid, causing input images to overflow into multiple output montages:

```bash
montage image1.png image2.jpg imageN.png -geometry +0+0 -tile 2x3 montage_%d.jpg
```

- Resize and crop images to fill their grid cells before tiling:

```bash
montage image1.png image2.jpg imageN.png -geometry +0+0 -resize 640x480^ -gravity center -crop 640x480+0+0 montage.jpg
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Seth Falco](mailto:seth@falco.fun) | *: fix errors reported by languagetool (#6069) | 2021-08-15T19:59:09 | [3e4c519004a4](https://github.com/tldr-pages/tldr/commit/3e4c519004a471c861cdc609fd7239ee3355671c)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | *: fix typos reported by Hunspell (#5848) Co-authored-by: marchersimon <50295997+marchersimon@users.noreply.github.com> Co-authored- [...] | 2021-05-20T22:13:41 | [8ebd171d6f00](https://github.com/tldr-pages/tldr/commit/8ebd171d6f001698709fefc02b1fd5cc9f3a99c4)
[pxgamer](mailto:owzie123@gmail.com) | montage: add link to homepage | 2019-06-04T21:29:40 | [eef0a04be7c5](https://github.com/tldr-pages/tldr/commit/eef0a04be7c5f0234a9fe189d501e05eb00235be)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | +"it" | 2016-01-14T12:25:40 | [c18b91ae67a9](https://github.com/tldr-pages/tldr/commit/c18b91ae67a9200eb774f2a896269ea87611769e)
[Starbeamrainbowlabs](mailto:sbrl@starbeamrainbowlabs.com) | Add imagemagick montage command to common Polish examples & descriptions Tweak to make it pass all the tests. Reword example text [...] | 2016-01-14T08:42:36 | [d13af3542798](https://github.com/tldr-pages/tldr/commit/d13af3542798285892af5570f743315663a4fd18)

