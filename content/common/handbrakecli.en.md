---
author: ['Waldir Pimenta', 'lord63', 'Marco Bonelli', 'Ruben Vereecken', 'Mat', 'Romain Prieto', 'Lucas Gabriel Schneider', 'bl-ue']
date: 1635806121
title: "handbrakecli, TLDR Pages"
description: "handbrakecli, Command-line interface to the HandBrake video conversion and DVD ripping tool."
categories: "common"
---
> More information: <https://handbrake.fr/>.

- Convert a video file to MKV (AAC 160kbit audio and x264 CRF20 video):

```bash
handbrakecli --input input.avi --output output.mkv --encoder x264 --quality 20 --ab 160
```

- Resize a video file to 320x240:

```bash
handbrakecli --input input.mp4 --output output.mp4 --width 320 --height 240
```

- List available presets:

```bash
handbrakecli --preset-list
```

- Convert an AVI video to MP4 using the Android preset:

```bash
handbrakecli --preset="Android" --input input.ext --output output.mp4
```

- Print the content of a DVD, getting the CSS keys in the process:

```bash
handbrakecli --input /dev/sr0 --title 0
```

- Rip the first track of a DVD in the specified device. Audiotracks and subtitle languages are specified as lists:

```bash
handbrakecli --input /dev/sr0 --title 1 --output out.mkv --format av_mkv --encoder x264 --subtitle 1,4,5 --audio 1,2 --aencoder copy --quality 23
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Mat](mailto:mtausig@users.noreply.github.com) | handbrakecli: Add commands to rip DVD; update options to long form (#7279) | 2021-11-01T23:35:21 | [54803a002388](https://github.com/tldr-pages/tldr/commit/54803a002388284b3ed32e03d3f06895f60f60b8)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | *: clean up token syntax delimiters (#5677) | 2021-04-04T02:08:57 | [289787c7e8c1](https://github.com/tldr-pages/tldr/commit/289787c7e8c1177742d23004198253154fe50c3c)
[Marco Bonelli](mailto:marco@mebeim.net) | Refactor: reword English pages' links' descriptions. | 2019-06-03T14:19:41 | [66abb98ce935](https://github.com/tldr-pages/tldr/commit/66abb98ce935c0f4516bf30c4d6da72180d5a3ab)
[Lucas Gabriel Schneider](mailto:lucas.schneider@sap.com) | multiple pages: add homepages (#3025) | 2019-05-14T18:06:07 | [5514f773e2df](https://github.com/tldr-pages/tldr/commit/5514f773e2dfcd02ab6bc87c7e02fa8f7fbe2f25)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | page format: lowercase command names consistently (#1083) | 2016-09-22T09:03:38 | [107248374447](https://github.com/tldr-pages/tldr/commit/1072483744475ab5a25c87e8eb7ed10c99dd6ed8)
[Ruben Vereecken](mailto:rubenvereecken@gmail.com) | Formatted all pages according to guidelines. | 2016-01-08T09:38:59 | [066582e8eab5](https://github.com/tldr-pages/tldr/commit/066582e8eab57bce9861cc8d379e158d61f1cc95)
[lord63](mailto:lord63.j@gmail.com) | Fix lint for common | 2015-10-23T02:02:34 | [56a7cba6568f](https://github.com/tldr-pages/tldr/commit/56a7cba6568fcdaaeca2ddf0b80341cfc7de6285)
[Romain Prieto](mailto:rprieto@users.noreply.github.com) | Rename HandBrakeCLI.md to handbrakecli.md So it's sorted by default next to all the other lowercase commands | 2014-10-01T16:12:19 | [221eadc3366d](https://github.com/tldr-pages/tldr/commit/221eadc3366d5a3059304e355bc789433dbbf4a9)

