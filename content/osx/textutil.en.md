---
author: ['Lucas Gabriel Schneider', 'meowmeowcat', 'Ivan Aracki']
date: 1642165187
title: "textutil"
description: "textutil, Used to manipulate text files of various formats."
categories: "osx"
---
> More information: <https://ss64.com/osx/textutil.html>.

- Display information about `foo.rtf`:

```bash
textutil -info foo.rtf
```

- Convert `foo.rtf` into `foo.html`:

```bash
textutil -convert html foo.rtf
```

- Convert rich text to normal text:

```bash
textutil foo.rtf -convert txt
```

- Convert `foo.txt` into `foo.rtf`, using Times 10 for the font:

```bash
textutil -convert rtf -font Times -fontsize 10 foo.txt
```

- Load all RTF files in the current directory, concatenates their contents, and writes the result out as `index.html` with the HTML title set to "Several Files":

```bash
textutil -cat html -title "Several Files" -output index.html *.rtf
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[meowmeowcat](mailto:meowmeowcat1211@gmail.com) | textutil, top: add link (#7629) | 2022-01-14T13:59:47 | [e2f4d81f6bd4](https://github.com/tldr-pages/tldr/commit/e2f4d81f6bd48fe667d0659b5cb165a2244c9f54)
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | multiple pages: format technical tokens (#5119) Co-authored-by: bl-ue <54780737+bl-ue@users.noreply.github.com> Co-authored-by: [...] | 2021-01-31T18:05:18 | [a5fe31bc47ae](https://github.com/tldr-pages/tldr/commit/a5fe31bc47aece3efa5e66b52b3cf384f27d5d72)
[Ivan Aracki](mailto:aracki.ivan@gmail.com) | textutil: add page (#2657) * textutil: add page | 2018-12-20T13:47:04 | [d9389de51c1d](https://github.com/tldr-pages/tldr/commit/d9389de51c1db5cb4396899a6e86152f80dd70c2)

