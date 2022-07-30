---
author: ['Robert Speicher', 'pxgamer', 'Marco Bonelli', 'Juri', 'Marvin Reimer', 'Leandro Ostera', 'Ruben Vereecken']
date: 1602507753
title: "exiftool"
description: "exiftool, Read and write meta information in files."
categories: "common"
---
> More information: <https://exiftool.org>.

- Remove all EXIF metadata from the given files:

```bash
exiftool -All= file1 file2 ...
```

- Move the date at which all photos in a directory were taken 1 hour forward:

```bash
exiftool "-AllDates+=0:0:0 1:0:0" path/to/directory
```

- Move the date at which all JPEG photos in the current directory were taken 1 day and 2 hours backward:

```bash
exiftool "-AllDates-=0:0:1 2:0:0" -ext jpg
```

- Only change the `DateTimeOriginal` field subtracting 1.5 hours, without keeping backups:

```bash
exiftool -DateTimeOriginal-=1.5 -overwrite_original
```

- Recursively rename all JPEG photos in a directory based on the `DateTimeOriginal` field:

```bash
exiftool '-filename<DateTimeOriginal' -d %Y-%m-%d_%H-%M-%S%%lc.%%e path/to/directory -r -ext jpg
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Juri](mailto:juri.dispan@posteo.net) | exiftool: fix more information link (#4648) | 2020-10-12T15:02:33 | [c9db672e4dae](https://github.com/tldr-pages/tldr/commit/c9db672e4dae9c35af8f9f7c0d210775857711ab)
[Marco Bonelli](mailto:mebeim@users.noreply.github.com) | exiftool: reword and clarify page. (#3324) | 2019-10-06T17:18:58 | [841ec0d9454c](https://github.com/tldr-pages/tldr/commit/841ec0d9454c8e23fec63f564ff11425e0ae527a)
[pxgamer](mailto:owzie123@gmail.com) | exiftool: add link to homepage | 2019-06-09T06:54:24 | [41def64e8f4e](https://github.com/tldr-pages/tldr/commit/41def64e8f4e7b992192dd8bf8e2bdbf440ca200)
[Leandro Ostera](mailto:leandro@ostera.io) | Formatting! | 2016-02-13T00:24:52 | [c701cca93054](https://github.com/tldr-pages/tldr/commit/c701cca93054295a84d6735215ad1e9148bb2310)
[Leandro Ostera](mailto:leandro@ostera.io) | Merge pull request #290 from therealmarv/more-exiftool add more exiftool examples | 2016-02-13T00:24:17 | [d8d204adee25](https://github.com/tldr-pages/tldr/commit/d8d204adee25d21e2031b17867451dfd448615e1)
[Ruben Vereecken](mailto:rubenvereecken@gmail.com) | Formatted all pages according to guidelines. | 2016-01-08T09:38:59 | [066582e8eab5](https://github.com/tldr-pages/tldr/commit/066582e8eab57bce9861cc8d379e158d61f1cc95)
[Marvin Reimer](mailto:therealmarv@gmail.com) | added more options based on github comments | 2015-08-19T23:37:44 | [65075cc8ce3a](https://github.com/tldr-pages/tldr/commit/65075cc8ce3ab3dfd685aacb5cfcd98b2a9836fb)
[Marvin Reimer](mailto:therealmarv@gmail.com) | remove verbose | 2015-08-16T00:11:59 | [1cc2dbc2118e](https://github.com/tldr-pages/tldr/commit/1cc2dbc2118e3365b3fc98d73897eb3171353faf)
[Marvin Reimer](mailto:therealmarv@gmail.com) | add more exiftool examples | 2015-08-15T17:04:31 | [6ff973c0fe8c](https://github.com/tldr-pages/tldr/commit/6ff973c0fe8c3194951425af5710be96c1fdd066)
[Robert Speicher](mailto:rspeicher@gmail.com) | Add exiftool and one example | 2014-04-12T19:25:30 | [43abf49b76da](https://github.com/tldr-pages/tldr/commit/43abf49b76da6f7f32be7f84bb4d3123b92f69fb)

