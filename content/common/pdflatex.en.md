---
author: ['85pando', 'marchersimon', 'Diogo Silva', 'chris']
date: 1629039659
title: "pdflatex"
description: "pdflatex, Compile a PDF document from LaTeX source files."
categories: "common"
---
> More information: <https://manned.org/pdflatex>.

- Compile a PDF document:

```bash
pdflatex source.tex
```

- Compile a PDF document specifying an output directory:

```bash
pdflatex -output-directory=path/to/directory source.tex
```

- Compile a PDF document, exiting on each error:

```bash
pdflatex -halt-on-error source.tex
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[chris](mailto:35269695+chrissxYT@users.noreply.github.com) | latex, pdflatex, pdftex, tex: replace `halting' with `exiting' (#6365) | 2021-08-15T17:00:59 | [62fe2a2a1094](https://github.com/tldr-pages/tldr/commit/62fe2a2a10942b3808bc2b6bfe1f2996e9fb8602)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | multiple pages: replace all die.net links (#5528) Most of the links were replaced by manned.org, except when there are more up-to-date [...] | 2021-04-16T16:42:14 | [dac4a710772f](https://github.com/tldr-pages/tldr/commit/dac4a710772f9adef5b9883172fb30ed2416c0eb)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | latex, pdftex, tex, texdoc, texliveonfly, tlmgr: add page (#5294) | 2021-02-28T14:33:40 | [0589644d0162](https://github.com/tldr-pages/tldr/commit/0589644d0162bec7390a9ad3b417effa0577bf7b)
[Diogo Silva](mailto:its.diogo.silva@gmail.com) | pdflatex: add -output-directory example (#3189) | 2019-07-15T21:59:47 | [9ccc84ce1709](https://github.com/tldr-pages/tldr/commit/9ccc84ce17094bacd33aafc9f93f415570a70430)
[85pando](mailto:85pando@googlemail.com) | Add pages for latexmk and pdflatex Pdflatex and latexmk are two tools to create Output documents from LaTeX source files. Added colons [...] | 2016-01-16T09:47:14 | [9a3eac64c01d](https://github.com/tldr-pages/tldr/commit/9a3eac64c01d6b134ccdceccb28347665621fe1a)

