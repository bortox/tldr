---
author: ['Gil Moskowitz', 'Waldir Pimenta', 'pxgamer', 'Andrey Bienkowski']
date: 1639130791
title: "groff"
description: "groff, GNU replacement for the `troff` and `nroff` typesetting utilities."
categories: "common"
---
> More information: <https://www.gnu.org/software/groff>.

- Format output for a PostScript printer, saving the output to a file:

```bash
groff path/to/input.roff > path/to/output.ps
```

- Render a man page using the ASCII output device, and display it using a pager:

```bash
groff -man -T ascii path/to/manpage.1 | less --RAW-CONTROL-CHARS
```

- Render a man page into an HTML file:

```bash
groff -man -T html path/to/manpage.1 > path/to/manpage.html
```

- Typeset a roff file containing [t]ables and [p]ictures, using the [me] macro set, to PDF, saving the output:

```bash
groff -t -p -me -T pdf path/to/input.me > path/to/output.pdf
```

- Run a `groff` command with preprocessor and macro options guessed by the `grog` utility:

```bash
eval "$(grog -T utf8 path/to/input.me)"
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Andrey Bienkowski](mailto:hexagonrecursion@gmail.com) | groff: add --RAW-CONTROL-CHARS to pager example (#7516) | 2021-12-10T11:06:31 | [5bdbc8ff8311](https://github.com/tldr-pages/tldr/commit/5bdbc8ff83114ab843fc43b7261391ee2d801083)
[Gil Moskowitz](mailto:gmoskowitz@xtuple.com) | eqn, grap, groff, pic, tbl, troff: add page (#6868) | 2021-10-21T09:17:15 | [318ca787e19a](https://github.com/tldr-pages/tldr/commit/318ca787e19a1aecc4526eae280a87292f38d654)
[pxgamer](mailto:owzie123@gmail.com) | groff: add link to homepage | 2019-06-07T23:58:59 | [408a0ad32f3c](https://github.com/tldr-pages/tldr/commit/408a0ad32f3c8535b356f4f3d5022818d2d6bfc4)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | Update groff.md | 2017-09-09T13:52:54 | [dee78902314d](https://github.com/tldr-pages/tldr/commit/dee78902314dd89c977e97d29c4a2b2421722745)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | groff: create page Sources: https://embswit.wordpress.com/2013/02/08/render-man-page-from-source/, and the EXAMPLES section of `man [...] | 2017-09-08T18:06:21 | [d6330e21076e](https://github.com/tldr-pages/tldr/commit/d6330e21076e7047b7c3c43443e6f5a0c80d1cb7)

