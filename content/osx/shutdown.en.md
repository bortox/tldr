---
author: ['Emily Grace Seville', 'Ruben Vereecken', 'Paul Galow', 'meowmeowcat', 'rprieto']
date: 1644837703
title: "shutdown, TLDR Pages"
description: "shutdown, Shutdown and reboot the system."
categories: "osx"
---
> More information: <https://ss64.com/osx/shutdown.html>.

- Power off (halt) immediately:

```bash
shutdown -h now
```

- Sleep immediately:

```bash
shutdown -s now
```

- Reboot immediately:

```bash
shutdown -r now
```

- Reboot in 5 minutes:

```bash
shutdown -r "+5"
```

- Power off (halt) at 1:00 pm (Uses 24h clock):

```bash
shutdown -h 1300
```

- Reboot on May 10th 2042 at 11:30 am (Input format: YYMMDDHHMM):

```bash
shutdown -r 4205101130
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Emily Grace Seville](mailto:emilyseville7cf@gmail.com) | osx/*: update page (#7665) | 2022-02-14T12:21:43 | [692469016e62](https://github.com/tldr-pages/tldr/commit/692469016e62d4410ec92a8f29272e447046a0d2)
[meowmeowcat](mailto:meowmeowcat1211@gmail.com) | osx/s*: add link (#7428) | 2021-11-14T20:45:59 | [a36f8550d81b](https://github.com/tldr-pages/tldr/commit/a36f8550d81be6fbe04cb43f3d0a34f30e024b86)
[Paul Galow](mailto:paulgalow@users.noreply.github.com) | shutdown: add absolute time examples (#3011) | 2019-05-12T12:40:28 | [76e0337df1e6](https://github.com/tldr-pages/tldr/commit/76e0337df1e630ac297de30ea2f4a71092fa6528)
[Ruben Vereecken](mailto:rubenvereecken@gmail.com) | Formatted all pages according to guidelines. | 2016-01-08T09:38:59 | [066582e8eab5](https://github.com/tldr-pages/tldr/commit/066582e8eab57bce9861cc8d379e158d61f1cc95)
[rprieto](mailto:choicesmade@gmail.com) | Move pages back into a "pages" folder | 2014-03-04T13:28:29 | [f00bf64426a7](https://github.com/tldr-pages/tldr/commit/f00bf64426a792ee3aac792f9c0aec3f8b1eaa7d)

