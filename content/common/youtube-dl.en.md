---
author: ['P_Q_H', 'empty', 'Marco Bonelli', 'David Cantrell', 'Krzysztof Bociurko', 'Atrate', 'Tayeb B', 'shyneko', 'Hayden Schiff', 'Miro Rauhala', 'Guido Lena Cota', 'Seth Falco', 'Starbeamrainbowlabs', 'Manuel Haussmann']
date: 1630497441
title: "youtube-dl, TLDR Pages"
description: "youtube-dl, Download videos from YouTube and other websites."
categories: "common"
---
> More information: <http://rg3.github.io/youtube-dl/>.

- Download a video or playlist:

```bash
youtube-dl 'https://www.youtube.com/watch?v=oHg5SJYRHA0'
```

- List all formats that a video or playlist is available in:

```bash
youtube-dl --list-formats 'https://www.youtube.com/watch?v=Mwa0_nE9H7A'
```

- Download a video or playlist at a specific quality:

```bash
youtube-dl --format "best[height<=480]" 'https://www.youtube.com/watch?v=oHg5SJYRHA0'
```

- Download the audio from a video and convert it to an MP3:

```bash
youtube-dl -x --audio-format mp3 'url'
```

- Download the best quality audio and video and merge them:

```bash
youtube-dl -f bestvideo+bestaudio 'url'
```

- Download video(s) as MP4 files with custom filenames:

```bash
youtube-dl --format mp4 -o "%(playlist_index)s-%(title)s by %(uploader)s on %(upload_date)s in %(playlist)s.%(ext)s" 'url'
```

- Download a particular language's subtitles along with the video:

```bash
youtube-dl --sub-lang en --write-sub 'https://www.youtube.com/watch?v=Mwa0_nE9H7A'
```

- Download a playlist and extract MP3s from it:

```bash
youtube-dl -f "bestaudio" --continue --no-overwrites --ignore-errors --extract-audio --audio-format mp3 -o "%(title)s.%(ext)s" url_to_playlist
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Manuel Haussmann](mailto:manuel.haussmann@mailbox.org) | youtube-dl: extend the custom filenames example (#6434) Extend the custom filenames example to also include the playlist_index (a [...] | 2021-09-01T13:57:21 | [2945238a01c6](https://github.com/tldr-pages/tldr/commit/2945238a01c6763cc2a765e519cb91a0f229e60e)
[Seth Falco](mailto:seth@falco.fun) | *: fix errors reported by languagetool (#6069) | 2021-08-15T19:59:09 | [3e4c519004a4](https://github.com/tldr-pages/tldr/commit/3e4c519004a471c861cdc609fd7239ee3355671c)
[empty](mailto:34548743+tminei@users.noreply.github.com) | youtube-dl: improve download a playlist and extract mp3 (#5037) | 2021-01-03T14:25:16 | [64a30d8d3a07](https://github.com/tldr-pages/tldr/commit/64a30d8d3a077b8bace03a463133d6a17cbc7362)
[Krzysztof Bociurko](mailto:chanibal@users.noreply.github.com) | youtube-dl: add Polish translation (#4900) | 2020-11-01T14:30:55 | [4b06377bad69](https://github.com/tldr-pages/tldr/commit/4b06377bad69922dc63d93cf8e9979cb218652ca)
[Atrate](mailto:Atrate@protonmail.com) | youtube-dl: add quotation marks (#4768) | 2020-10-19T20:53:00 | [3851c1581273](https://github.com/tldr-pages/tldr/commit/3851c1581273373d561eafdeaaff65acb2b152da)
[Guido Lena Cota](mailto:guido.lenacota@kreuzwerker.de) | Bulk change: move double quotes outside tokens (#4431) | 2020-10-04T19:33:38 | [354d4b8748ee](https://github.com/tldr-pages/tldr/commit/354d4b8748ee58813dd6830ced7c3b11067255d7)
[shyneko](mailto:34548743+tminei@users.noreply.github.com) | youtube-dl: add download playlist example (#4174) | 2020-07-21T21:46:21 | [66bfc92e70b2](https://github.com/tldr-pages/tldr/commit/66bfc92e70b2f9bd8578dd3eab1aa556104ccb8e)
[David Cantrell](mailto:david@cantrell.org.uk) | youtube-dl: add subtitle options (#3992) | 2020-04-19T15:17:24 | [96cf62bc254b](https://github.com/tldr-pages/tldr/commit/96cf62bc254ba8d23f8b4323c4724f75300d0909)
[Miro Rauhala](mailto:4082806+mirorauhala@users.noreply.github.com) | youtube-dl: add download the best audio+video (#3790) * youtube-dl: add download the best audio+video With this command the user can [...] | 2020-01-26T13:53:12 | [9bd9afa6bdfd](https://github.com/tldr-pages/tldr/commit/9bd9afa6bdfd5a008887b689e8da1427d2b14c3d)
[Tayeb B](mailto:tasinttttttt@users.noreply.github.com) | youtube-dl: fix format syntax (#3175) | 2019-07-05T18:32:58 | [101a44292eae](https://github.com/tldr-pages/tldr/commit/101a44292eae59e778d819db5c27949e447491bb)
[Marco Bonelli](mailto:marco@mebeim.net) | Refactor: reword English pages' links' descriptions. | 2019-06-03T14:19:41 | [66abb98ce935](https://github.com/tldr-pages/tldr/commit/66abb98ce935c0f4516bf30c4d6da72180d5a3ab)
[P_Q_H](mailto:keatingsmitht@gmail.com) | youtube-dl: add example for the --format option (#2714) | 2019-02-25T06:34:32 | [04ae522268ce](https://github.com/tldr-pages/tldr/commit/04ae522268cec8b5f6e0529366a21a400c267aad)
[Starbeamrainbowlabs](mailto:sbrl@starbeamrainbowlabs.com) | multiple pages: add homepages (#2660) | 2019-01-30T12:19:23 | [a19866e88add](https://github.com/tldr-pages/tldr/commit/a19866e88addb239484637579b17e7c6ea9b53aa)
[P_Q_H](mailto:keatingsmitht@gmail.com) | youtube-dl: fix custom filename example (#2708) | 2019-01-15T00:45:13 | [9749d6fc47b6](https://github.com/tldr-pages/tldr/commit/9749d6fc47b6f57efaff934be9aabadd8734ab64)
[Hayden Schiff](mailto:oxguy3@gmail.com) | youtube-dl: clearer description of mp3 example | 2016-01-22T00:56:49 | [790a4234b9a4](https://github.com/tldr-pages/tldr/commit/790a4234b9a4f49c43859e4b8093b63bc46972e6)
[Hayden Schiff](mailto:oxguy3@gmail.com) | added youtube-dl Not so sure about the last example. I wanted to give an example of how youtube-dl allows you to very precisely filter [...] | 2016-01-22T00:15:46 | [8cf1d291117c](https://github.com/tldr-pages/tldr/commit/8cf1d291117cf2f46a84e323d12b9de6e21a807b)

