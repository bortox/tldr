---
author: ['Waldir Pimenta', 'Srinivasan R', 'lord63', 'Ruben Vereecken', 'pxgamer', 'Romain Prieto', 'bl-ue', 'Te-Chi Liu']
date: 1617494937
title: "mp4box, TLDR Pages"
description: "mp4box, MPEG-4 Systems Toolbox - Muxes streams into MP4 container."
categories: "common"
---
> More information: <https://gpac.wp.imt.fr/mp4box>.

- Display information about an existing MP4 file:

```bash
mp4box -info filename
```

- Add an SRT subtitle file into an MP4 file:

```bash
mp4box -add input_subs.srt:lang=eng -add input.mp4 output.mp4
```

- Combine audio from one file and video from another:

```bash
mp4box -add input1.mp4#audio -add input2.mp4#video output.mp4
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | *: clean up token syntax delimiters (#5677) | 2021-04-04T02:08:57 | [289787c7e8c1](https://github.com/tldr-pages/tldr/commit/289787c7e8c1177742d23004198253154fe50c3c)
[pxgamer](mailto:owzie123@gmail.com) | mp4box: add link to homepage | 2019-06-04T21:29:40 | [8c728e9551a3](https://github.com/tldr-pages/tldr/commit/8c728e9551a3076ecf43931fbc0409a489a71d3d)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | page format: lowercase command names consistently (#1083) | 2016-09-22T09:03:38 | [107248374447](https://github.com/tldr-pages/tldr/commit/1072483744475ab5a25c87e8eb7ed10c99dd6ed8)
[Te-Chi Liu](mailto:liuderchi@gmail.com) | fixup: token string style (#1081) - use underscore rather than minus - use lower case rather than uppder case | 2016-09-21T17:35:46 | [5a54763c72d1](https://github.com/tldr-pages/tldr/commit/5a54763c72d1ed1b6eb5dbf195ee547527afc608)
[Ruben Vereecken](mailto:rubenvereecken@gmail.com) | Formatted all pages according to guidelines. | 2016-01-08T09:38:59 | [066582e8eab5](https://github.com/tldr-pages/tldr/commit/066582e8eab57bce9861cc8d379e158d61f1cc95)
[Srinivasan R](mailto:srinivasanr@gmail.com) | Normalize the final new line Fixes #310 Some files had no newlines, some had 1 newline and some more than 1 newline. Normalize them [...] | 2015-10-28T09:33:06 | [e4114fa6cce7](https://github.com/tldr-pages/tldr/commit/e4114fa6cce7339425809afef817b06e872d7ca7)
[lord63](mailto:lord63.j@gmail.com) | Fix lint for common | 2015-10-23T02:02:34 | [56a7cba6568f](https://github.com/tldr-pages/tldr/commit/56a7cba6568fcdaaeca2ddf0b80341cfc7de6285)
[Romain Prieto](mailto:rprieto@users.noreply.github.com) | Rename MP4Box.md to mp4box.md So it's sorted by default next to all the other lowercase commands | 2014-10-01T16:12:29 | [4f6e05fb1ef1](https://github.com/tldr-pages/tldr/commit/4f6e05fb1ef15ff5f3d9ae49420819ebbe9a28f7)

