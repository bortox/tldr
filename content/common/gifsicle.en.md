---
author: ['rprieto', 'pxgamer', 'Waldir Pimenta', 'Starbeamrainbowlabs', 'Cairn', 'Ruben Vereecken']
date: 1661888943
title: "gifsicle"
description: "gifsicle, GIF manipulator."
categories: "common"
---
> More information: <https://www.lcdf.org/gifsicle>.

- Optimize a GIF as a new file:

```bash
gifsicle path/to/input.gif --optimize=3 -o path/to/output.gif
```

- Unoptimize a GIF in place:

```bash
gifsicle -b path/to/input.gif --unoptimize
```

- Extract a frame from a GIF:

```bash
gifsicle path/to/input.gif '#0' > path/to/firstframe.gif
```

- Make a GIF animation from selected GIFs:

```bash
gifsicle *.gif --delay=10 --loop > path/to/output.gif
```

- Reduce file size using lossy compression:

```bash
gifsicle -b path/to/input.gif --optimize=3 --lossy=100 --colors=16 --dither
```

- Delete the first 10 frames and all frames after frame 20 from a GIF:

```bash
gifsicle -b path/to/input.gif --delete '#0-9' '#20-'
```

- Modify all frames of a GIF using specific transformation options:

```bash
gifsicle -b --crop 50,50+-50x-50 --scale 0.25 --flip-horizontal --rotate-90 path/to/input.gif
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Cairn](mailto:cairn@pm.me) | gifsicle: update page (#8403) | 2022-08-30T21:49:03 | [d360ef4418f4](https://github.com/tldr-pages/tldr/commit/d360ef4418f46bb1f020364e0751683d89e3a6b3)
[pxgamer](mailto:owzie123@gmail.com) | gifsicle: add link to homepage | 2019-06-07T23:58:59 | [7422c65da9de](https://github.com/tldr-pages/tldr/commit/7422c65da9de955501a0c0f4936ccdaa9158648d)
[Starbeamrainbowlabs](mailto:sbrl@starbeamrainbowlabs.com) | gifsicle: Add optimise example | 2018-07-06T09:23:56 | [e176566748bd](https://github.com/tldr-pages/tldr/commit/e176566748bded6926749c7df34e7debcf04c517)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | gifsicle: minor capitalization fix | 2018-01-18T19:48:27 | [fa274ad9f19e](https://github.com/tldr-pages/tldr/commit/fa274ad9f19e87c0522953dd68f3dae673af2765)
[Ruben Vereecken](mailto:rubenvereecken@gmail.com) | Fixed English tenses as reported by tldr-lint | 2016-01-16T15:12:05 | [5a26958e942c](https://github.com/tldr-pages/tldr/commit/5a26958e942c16ccf9eb1a58bfe4e410b1707e64)
[Ruben Vereecken](mailto:rubenvereecken@gmail.com) | Formatted all pages according to guidelines. | 2016-01-08T09:38:59 | [066582e8eab5](https://github.com/tldr-pages/tldr/commit/066582e8eab57bce9861cc8d379e158d61f1cc95)
[rprieto](mailto:choicesmade@gmail.com) | Move pages back into a "pages" folder | 2014-03-04T13:28:29 | [f00bf64426a7](https://github.com/tldr-pages/tldr/commit/f00bf64426a792ee3aac792f9c0aec3f8b1eaa7d)

