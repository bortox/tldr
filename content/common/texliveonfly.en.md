---
author: ['marchersimon']
date: 1614519220
title: "texliveonfly, TLDR Pages"
description: "texliveonfly, Downloads missing TeX Live packages while compiling `.tex` files."
categories: "common"
---
> More information: <https://ctan.org/pkg/texliveonfly>.

- Download missing packages while compiling:

```bash
texliveonfly source.tex
```

- Use a specific compiler (defaults to `pdflatex`):

```bash
texliveonfly --compiler=compiler source.tex
```

- Use a custom TeX Live `bin` folder:

```bash
texliveonfly --texlive_bin=path/to/texlive_bin source.tex
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | latex, pdftex, tex, texdoc, texliveonfly, tlmgr: add page (#5294) | 2021-02-28T14:33:40 | [0589644d0162](https://github.com/tldr-pages/tldr/commit/0589644d0162bec7390a9ad3b417effa0577bf7b)

