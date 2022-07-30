---
author: ['John Jekel', 'JZJisawesome', 'pxgamer', 'Marco Bonelli']
date: 1564927515
title: "enscript"
description: "enscript, Convert text files to PostScript, HTML, RTF, ANSI, and overstrikes."
categories: "common"
---
> More information: <https://www.gnu.org/software/enscript>.

- Generate a PostScript file from a text file:

```bash
enscript path/to/input_file --output=path/to/output_file
```

- Generate a file in a different language than PostScript:

```bash
enscript path/to/input_file --language=html|rtf|... --output=path/to/output_file
```

- Generate a PostScript file with a landscape layout, splitting the page into columns (maximum 9):

```bash
enscript path/to/input_file --columns=num --landscape --output=path/to/output_file
```

- Display available syntax highlighting languages and file formats:

```bash
enscript --help-highlight
```

- Generate a PostScript file with syntax highlighting and color for a specified language:

```bash
enscript path/to/input_file --color=1 --highlight=language --output=path/to/output_file
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Marco Bonelli](mailto:mebeim@users.noreply.github.com) | enscript: reword page (#3220) | 2019-08-04T16:05:15 | [9bd20d5328e5](https://github.com/tldr-pages/tldr/commit/9bd20d5328e50e08ce368d31a6b445de4b4e2273)
[pxgamer](mailto:owzie123@gmail.com) | enscript: add link to homepage | 2019-06-09T06:54:24 | [c9ee7c0eb90e](https://github.com/tldr-pages/tldr/commit/c9ee7c0eb90e291831bff9280e5f38de633af08e)
[John Jekel](mailto:40674968+JZJisawesome@users.noreply.github.com) | enscript: fix typos (#2446) | 2018-10-15T09:10:09 | [ed930911b323](https://github.com/tldr-pages/tldr/commit/ed930911b3237862037d5e964f58d628c3523d2e)
[JZJisawesome](mailto:40674968+JZJisawesome@users.noreply.github.com) | enscript: add page (#2432) | 2018-10-12T20:11:09 | [01146452dd5d](https://github.com/tldr-pages/tldr/commit/01146452dd5da5f1190b314e33bab626a166db76)

