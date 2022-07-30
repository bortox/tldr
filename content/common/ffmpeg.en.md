---
author: ['Michael Neeley', 'Agniva De Sarker', 'Eric Rösch', 'Lucas Gabriel Schneider', 'Jesse Smith', 'Peter Tripp', 'Francesco Yoshi Gobbo', 'Henry Vindin', 'lord63', 'pxgamer', 'Ruben Vereecken']
date: 1654353340
title: "ffmpeg"
description: "ffmpeg, Video conversion tool."
categories: "common"
---
> More information: <https://ffmpeg.org>.

- Extract the sound from a video and save it as MP3:

```bash
ffmpeg -i video.mp4 -vn sound.mp3
```

- Save a video as GIF, scaling the height to 1000px and setting framerate to 15:

```bash
ffmpeg -i video.mp4 -vf 'scale=-1:1000' -r 15 output.gif
```

- Combine numbered images (`frame_1.jpg`, `frame_2.jpg`, etc) into a video or GIF:

```bash
ffmpeg -i frame_%d.jpg -f image2 video.mpg|video.gif
```

- Quickly extract a single frame from a video at time mm:ss and save it as a 128x128 resolution image:

```bash
ffmpeg -ss mm:ss -i video.mp4 -frames 1 -s 128x128 -f image2 image.png
```

- Trim a video from a given start time mm:ss to an end time mm2:ss2 (omit the -to flag to trim till the end):

```bash
ffmpeg -ss mm:ss -to mm2:ss2 -i video.mp4 -codec copy output.mp4
```

- Convert AVI video to MP4. AAC Audio @ 128kbit, h264 Video @ CRF 23:

```bash
ffmpeg -i input_video.avi -codec:audio aac -b:audio 128k -codec:video libx264 -crf 23 output_video.mp4
```

- Remux MKV video to MP4 without re-encoding audio or video streams:

```bash
ffmpeg -i input_video.mkv -codec copy output_video.mp4
```

- Convert MP4 video to VP9 codec. For the best quality, use a CRF value (recommended range 15-35) and -b:video MUST be 0:

```bash
ffmpeg -i input_video.mp4 -codec:video libvpx-vp9 -crf 30 -b:video 0 -codec:audio libopus -vbr on -threads number_of_threads output_video.webm
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Michael Neeley](mailto:micneeley14@gmail.com) | ffmpeg: replace with -vf and -r example (#8113) | 2022-06-04T16:35:40 | [7e46b4a2686c](https://github.com/tldr-pages/tldr/commit/7e46b4a2686c75b121834dc9318a25c3b1b2854c)
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | multiple pages: format technical tokens (#5119) Co-authored-by: bl-ue <54780737+bl-ue@users.noreply.github.com> Co-authored-by: [...] | 2021-01-31T18:05:18 | [a5fe31bc47ae](https://github.com/tldr-pages/tldr/commit/a5fe31bc47aece3efa5e66b52b3cf384f27d5d72)
[pxgamer](mailto:owzie123@gmail.com) | ffmpeg: add link to homepage | 2019-06-07T23:58:59 | [99b5e8584d37](https://github.com/tldr-pages/tldr/commit/99b5e8584d37085bba6b5fe43d0566f95d9444ad)
[Francesco Yoshi Gobbo](mailto:yoshi@fgobbo.com) | ffmpeg: simplified video trimming (#2232) | 2018-08-12T18:20:09 | [4a2d83c6aff3](https://github.com/tldr-pages/tldr/commit/4a2d83c6aff35d25f3099779e5d2e4a2210cab6f)
[Francesco Yoshi Gobbo](mailto:yoshi@fgobbo.com) | ffmpeg: added trim example plus augmented precision to seconds (#2099) | 2018-05-06T20:28:30 | [a3ac6db8d27b](https://github.com/tldr-pages/tldr/commit/a3ac6db8d27bf30fce84380f14f70935888cf320)
[Francesco Yoshi Gobbo](mailto:yoshi@fgobbo.com) | Update ffmpeg.md if so → and | 2017-12-28T13:29:45 | [39099ebea36a](https://github.com/tldr-pages/tldr/commit/39099ebea36ad196e671b58485f6fa68b28af5ae)
[Agniva De Sarker](mailto:agnivade@yahoo.co.in) | ffmpeg: add tokens around crf value | 2017-12-28T13:05:56 | [0a5a374553df](https://github.com/tldr-pages/tldr/commit/0a5a374553df17da8da13a4e6f410e19d4663bfc)
[Francesco Yoshi Gobbo](mailto:yoshi@fgobbo.com) | adjustaments It's long but don't really know how to short this description line more ^^" I've added the long forms of `c:` and `b:v`. [...] | 2017-12-28T12:34:56 | [f90823802f8e](https://github.com/tldr-pages/tldr/commit/f90823802f8e08faa2282bf48da076dd32cb0142)
[Francesco Yoshi Gobbo](mailto:yoshi@fgobbo.com) | ffmpeg vp9 conversion Added sample command to convert an *.mp4 file to *.webm VP9 | 2017-12-07T15:15:22 | [054052d9e0f8](https://github.com/tldr-pages/tldr/commit/054052d9e0f8398bb057ce00dee8072cf4326302)
[Henry Vindin](mailto:henry@hcv.ind.in) | fixed wording and typos | 2017-10-28T13:59:12 | [7682d8bd877a](https://github.com/tldr-pages/tldr/commit/7682d8bd877a9b9c3b56887ecdac5a81345b401d)
[Henry Vindin](mailto:henry@hcv.ind.in) | update to simplify the tldr page based on feedback | 2017-10-28T13:59:06 | [32347f83a418](https://github.com/tldr-pages/tldr/commit/32347f83a4180ede781ff61e0b11e3f745bc686e)
[Henry Vindin](mailto:hvindin@westpac.com.au) | remove trailing whitespace | 2017-10-28T13:58:59 | [4dcb79878870](https://github.com/tldr-pages/tldr/commit/4dcb7987887082372235447d14e6b7a111ce3ad3)
[Henry Vindin](mailto:hvindin@westpac.com.au) | add more examples to ffmpeg based on examples in ffmpeg site docs | 2017-10-28T13:58:52 | [999df15f7cc3](https://github.com/tldr-pages/tldr/commit/999df15f7cc348d45f8fe7b5113a10aa44a37625)
[Jesse Smith](mailto:slicer69@users.noreply.github.com) | Simplify conversion/extraction example (#1502) | 2017-09-25T16:59:11 | [22791d16c941](https://github.com/tldr-pages/tldr/commit/22791d16c941ae9089cf2442607fdee121218186)
[Agniva De Sarker](mailto:agnivade@yahoo.co.in) | ffmpeg: add extract frame example and other tweaks (#1477) | 2017-09-23T06:11:41 | [7cce91b3c0b1](https://github.com/tldr-pages/tldr/commit/7cce91b3c0b1c8a97619df8dd845dbdad0f57b28)
[Eric Rösch](mailto:eric.roesch@web.de) | ffmpeg: also mention conversion of frames from GIF into numbered images and back (#1210) | 2016-12-24T01:29:40 | [086eca1cc20f](https://github.com/tldr-pages/tldr/commit/086eca1cc20fd40854765fa72f653d5881d9462b)
[Agniva De Sarker](mailto:agnivade@yahoo.co.in) | Applying the snake_case convention throughout the repo (#967) * Applying the snake_case convention throughout the repo - Also removing [...] | 2016-07-22T22:24:06 | [3da76e4150b8](https://github.com/tldr-pages/tldr/commit/3da76e4150b8631fd74aabfcc953cc23731b6bb8)
[Ruben Vereecken](mailto:rubenvereecken@gmail.com) | Formatted all pages according to guidelines. | 2016-01-08T09:38:59 | [066582e8eab5](https://github.com/tldr-pages/tldr/commit/066582e8eab57bce9861cc8d379e158d61f1cc95)
[lord63](mailto:lord63.j@gmail.com) | Fix lint for common | 2015-10-23T02:02:34 | [56a7cba6568f](https://github.com/tldr-pages/tldr/commit/56a7cba6568fcdaaeca2ddf0b80341cfc7de6285)
[Peter Tripp](mailto:petertripp@gmail.com) | Added ffmpeg, haxelib, Matt's Traceroute and imagemagick convert. | 2014-05-30T20:27:55 | [66b8ce3fc65d](https://github.com/tldr-pages/tldr/commit/66b8ce3fc65d526613a4886e49c607201d92512f)

