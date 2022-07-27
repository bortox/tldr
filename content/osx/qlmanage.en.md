---
author: ['Jeef', 'Emily Grace Seville', 'Ruben Vereecken', 'Agniva De Sarker', 'Arvid Gerstmann', 'rprieto', 'bl-ue']
date: 1644837703
title: "qlmanage, TLDR Pages"
description: "qlmanage, QuickLook server tool."
categories: "osx"
---
> More information: <https://ss64.com/osx/qlmanage.html>.

- Display QuickLook for one or multiple files:

```bash
qlmanage -p filename filename2
```

- Compute 300px wide PNG thumbnails of all JPEGs in the current directory and put them in a directory:

```bash
qlmanage *.jpg -t -s 300 path/to/directory
```

- Reset QuickLook:

```bash
qlmanage -r
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Emily Grace Seville](mailto:emilyseville7cf@gmail.com) | osx/*: update page (#7665) | 2022-02-14T12:21:43 | [692469016e62](https://github.com/tldr-pages/tldr/commit/692469016e62d4410ec92a8f29272e447046a0d2)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | *: fix typos reported by Hunspell (#5848) Co-authored-by: marchersimon <50295997+marchersimon@users.noreply.github.com> Co-authored- [...] | 2021-05-20T22:13:41 | [8ebd171d6f00](https://github.com/tldr-pages/tldr/commit/8ebd171d6f001698709fefc02b1fd5cc9f3a99c4)
[Agniva De Sarker](mailto:agnivade@yahoo.co.in) | update qlimage.md Wrapped some values in tokens. | 2017-03-01T17:56:43 | [8c89cf46136a](https://github.com/tldr-pages/tldr/commit/8c89cf46136aa6285189f7a5c6e86e50218f22ba)
[Jeef](mailto:jeeftor@users.noreply.github.com) | Update qlmanage.md | 2017-03-01T17:56:43 | [9cbf518ad350](https://github.com/tldr-pages/tldr/commit/9cbf518ad3506b7aa4a1c73bd12e7a197be9845f)
[Arvid Gerstmann](mailto:ag@arvid.io) | fix qlmanage page | 2016-04-15T17:21:10 | [88a974265f62](https://github.com/tldr-pages/tldr/commit/88a974265f62bc60f19e4483a9df2095b1827168)
[Ruben Vereecken](mailto:rubenvereecken@gmail.com) | Fixed English tenses as reported by tldr-lint | 2016-01-16T15:12:05 | [5a26958e942c](https://github.com/tldr-pages/tldr/commit/5a26958e942c16ccf9eb1a58bfe4e410b1707e64)
[Ruben Vereecken](mailto:rubenvereecken@gmail.com) | Formatted all pages according to guidelines. | 2016-01-08T09:38:59 | [066582e8eab5](https://github.com/tldr-pages/tldr/commit/066582e8eab57bce9861cc8d379e158d61f1cc95)
[rprieto](mailto:choicesmade@gmail.com) | Move pages back into a "pages" folder | 2014-03-04T13:28:29 | [f00bf64426a7](https://github.com/tldr-pages/tldr/commit/f00bf64426a792ee3aac792f9c0aec3f8b1eaa7d)

