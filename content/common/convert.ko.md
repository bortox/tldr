---
author: ['lch7167', 'bl-ue']
date: 1621541621
title: "convert, TLDR Pages"
description: "convert, ImageMagick 이미지 변환 도구."
categories: "common"
---
> 더 많은 정보: <https://imagemagick.org/script/convert.php>.

- JPG이미지를 PNG이미지로 변환:

```bash
convert 이미지.jpg 이미지.png
```

- 이미지를 원래 크기의 50%로 조정:

```bash
convert 이미지.png -resize 50% 이미지2.png
```

- 원래 종횡비를 유지하면서 이미지를 최대 640x480 크기로 조정:

```bash
convert 이미지.png -resize 640x480 이미지2.png
```

- 이미지를 가로로 추가:

```bash
convert 이미지1.png 이미지2.png 이미지3.png +append 이미지123.png
```

- 이미지를 세로로 추가:

```bash
convert 이미지1.png 이미지2.png 이미지3.png -append 이미지123.png
```

- 100ms 지연된 일련의 이미지에서 GIF 만들기:

```bash
convert 이미지1.png 이미지2.png 이미지3.png -delay 100 애니메이션.gif
```

- 단색 배경만으로 이미지 만들기:

```bash
convert -size 800x600 "xc:#ff0000" 이미지.png
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | *: fix typos reported by Hunspell (#5848) Co-authored-by: marchersimon <50295997+marchersimon@users.noreply.github.com> Co-authored- [...] | 2021-05-20T22:13:41 | [8ebd171d6f00](https://github.com/tldr-pages/tldr/commit/8ebd171d6f001698709fefc02b1fd5cc9f3a99c4)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | *: trim multiple spaces, fix line endings | 2021-04-04T01:44:24 | [04dd546e2de7](https://github.com/tldr-pages/tldr/commit/04dd546e2de7f59f40a867acca6f46b0dc8ea9b4)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | multiple pages: normalize line endings from CRLF to LF | 2021-01-12T15:36:36 | [567dc4ce0663](https://github.com/tldr-pages/tldr/commit/567dc4ce0663231ea1b8b9533b327094eb82ba1f)
[lch7167](mailto:youngsj69@gmail.com) | merge consul_to_cowsay (#3593) | 2019-11-22T16:21:20 | [3b31dfcc59bf](https://github.com/tldr-pages/tldr/commit/3b31dfcc59bf4f74075db7af37e193eebde977df)

