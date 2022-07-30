---
author: ['Waldir Pimenta', 'rprieto', 'pxgamer', 'Starbeamrainbowlabs', 'Ruben Vereecken']
date: 1559944739
title: "gifsicle"
description: "gifsicle, Create GIFs."
categories: "common"
---
> More information: <https://www.lcdf.org/gifsicle>.

- Optimise a GIF:

```bash
gifsicle --batch --optimize=3 amin.gif
```

- Make a GIF animation with gifsicle:

```bash
gifsicle --delay=10 --loop *.gif > anim.gif
```

- Extract frames from an animation:

```bash
gifsicle anim.gif '#0' > firstframe.gif
```

- You can also edit animations by replacing, deleting, or inserting frames:

```bash
gifsicle -b anim.gif --replace '#0' new.gif
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[pxgamer](mailto:owzie123@gmail.com) | gifsicle: add link to homepage | 2019-06-07T23:58:59 | [7422c65da9de](https://github.com/tldr-pages/tldr/commit/7422c65da9de955501a0c0f4936ccdaa9158648d)
[Starbeamrainbowlabs](mailto:sbrl@starbeamrainbowlabs.com) | gifsicle: Add optimise example | 2018-07-06T09:23:56 | [e176566748bd](https://github.com/tldr-pages/tldr/commit/e176566748bded6926749c7df34e7debcf04c517)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | gifsicle: minor capitalization fix | 2018-01-18T19:48:27 | [fa274ad9f19e](https://github.com/tldr-pages/tldr/commit/fa274ad9f19e87c0522953dd68f3dae673af2765)
[Ruben Vereecken](mailto:rubenvereecken@gmail.com) | Fixed English tenses as reported by tldr-lint | 2016-01-16T15:12:05 | [5a26958e942c](https://github.com/tldr-pages/tldr/commit/5a26958e942c16ccf9eb1a58bfe4e410b1707e64)
[Ruben Vereecken](mailto:rubenvereecken@gmail.com) | Formatted all pages according to guidelines. | 2016-01-08T09:38:59 | [066582e8eab5](https://github.com/tldr-pages/tldr/commit/066582e8eab57bce9861cc8d379e158d61f1cc95)
[rprieto](mailto:choicesmade@gmail.com) | Move pages back into a "pages" folder | 2014-03-04T13:28:29 | [f00bf64426a7](https://github.com/tldr-pages/tldr/commit/f00bf64426a792ee3aac792f9c0aec3f8b1eaa7d)

