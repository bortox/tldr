---
author: ['Waldir Pimenta', 'Daniel Senff', 'pxgamer', 'Jeef', 'Ruben Vereecken']
date: 1559133670
title: "sox"
description: "sox, Sound eXchange: play, record and convert audio files."
categories: "common"
---
> Audio formats are identified by the extension.

> More information: <http://sox.sourceforge.net>.

- Merge two audio files into one:

```bash
sox -m input_audiofile1 input_audiofile2 output_audiofile
```

- Trim an audio file to the specified times:

```bash
sox input_audiofile output_audiofile trim start end
```

- Normalize an audio file (adjust volume to the maximum peak level, without clipping):

```bash
sox --norm input_audiofile output_audiofile
```

- Reverse and save an audio file:

```bash
sox input_audiofile output_audiofile reverse
```

- Print statistical data of an audio file:

```bash
sox input_audiofile -n stat
```

- Increase the volume of an audio file by 2x:

```bash
sox -v 2.0 input_audiofile output_audiofile
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[pxgamer](mailto:owzie123@gmail.com) | multiple pages: update the web link descriptions | 2019-05-29T14:41:10 | [f2b1446e6247](https://github.com/tldr-pages/tldr/commit/f2b1446e6247d3e794ee6577dee0c867dfc9af26)
[pxgamer](mailto:owzie123@gmail.com) | sox: add link to homepage | 2019-05-29T14:41:10 | [1426bff3d4af](https://github.com/tldr-pages/tldr/commit/1426bff3d4af84a3dd0d784fa8e76e365436ddf9)
[Jeef](mailto:jeeftor@users.noreply.github.com) | sox: add example of changing the volume of a file (#1242) | 2017-01-26T23:46:42 | [43c3e68c5b27](https://github.com/tldr-pages/tldr/commit/43c3e68c5b27687018070e5142f258f533ce894a)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | fix descriptions split by mistake in #633 (#1098) | 2016-10-12T17:58:04 | [c15d705d4007](https://github.com/tldr-pages/tldr/commit/c15d705d4007cc9adfa737a0ec6b88bef56656a8)
[Ruben Vereecken](mailto:rubenvereecken@gmail.com) | Formatted all pages according to guidelines. | 2016-01-08T09:38:59 | [066582e8eab5](https://github.com/tldr-pages/tldr/commit/066582e8eab57bce9861cc8d379e158d61f1cc95)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | make filenames consistent across examples | 2014-09-29T04:18:13 | [2a0cf1eac27f](https://github.com/tldr-pages/tldr/commit/2a0cf1eac27fe171f928503ed1f871da7fe1b42d)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | several tweaks to sox.md for consistency and clarity | 2014-09-29T04:15:39 | [5cf0fc11c52d](https://github.com/tldr-pages/tldr/commit/5cf0fc11c52d5975e2e397c4f7c330d0700887df)
[Daniel Senff](mailto:mail@danielsenff.de) | Add sox and play commands for sox sound processing | 2014-09-26T15:45:32 | [6136fbe731fe](https://github.com/tldr-pages/tldr/commit/6136fbe731fe95c6e564421ece6d516c48f712ef)

