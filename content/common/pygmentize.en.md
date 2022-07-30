---
author: ['Joshua Shanks', 'Waldir Pimenta', 'Rudinski Zvonimir', 'Agniva De Sarker']
date: 1633557112
title: "pygmentize"
description: "pygmentize, Python-based syntax highlighter."
categories: "common"
---
> More information: <https://pygments.org/docs/cmdline/>.

- Highlight file syntax and print to standard output (language is inferred from the file extension):

```bash
pygmentize file.py
```

- Explicitly set the language for syntax highlighting:

```bash
pygmentize -l javascript input_file
```

- List available lexers (processors for input languages):

```bash
pygmentize -L lexers
```

- Save output to a file in HTML format:

```bash
pygmentize -f html -o output_file.html input_file.py
```

- List available output formats:

```bash
pygmentize -L formatters
```

- Output an HTML file, with additional formatter options (full page, with line numbers):

```bash
pygmentize -f html -O "full,linenos=True" -o output_file.html input_file
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Joshua Shanks](mailto:jjshanks@gmail.com) | ps, pv, pygmentize, quota, rabin2: add link (#6830) | 2021-10-06T23:51:52 | [52b9aaf74c57](https://github.com/tldr-pages/tldr/commit/52b9aaf74c571d0ee04b6f2986e09fff22ba7256)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | pygmentize: various tweaks (#1355) * pygmentize: various tweaks - adjust punctuation in main description and first example's [...] | 2017-05-03T21:54:49 | [7a9c755e4e5d](https://github.com/tldr-pages/tldr/commit/7a9c755e4e5d6569a632f6594c41f8693fa549e1)
[Rudinski Zvonimir](mailto:zvonimirurdinski@protonmail.ch) | minor changes | 2017-04-28T09:28:19 | [4a0662a95ec0](https://github.com/tldr-pages/tldr/commit/4a0662a95ec0a1d0e45a07dfd76f351de55fbe16)
[Agniva De Sarker](mailto:agnivade@yahoo.co.in) | Simplify pygmentize - Simplify main description - Mentioning that language is inferred from file extension - Giving a concrete example [...] | 2017-04-28T09:28:19 | [d49b95fc53c1](https://github.com/tldr-pages/tldr/commit/d49b95fc53c10f46bd09faaf2503dbc577cdaf9e)
[Rudinski Zvonimir](mailto:zvonimirurdinski@protonmail.ch) | add pygmentize | 2017-04-28T09:28:19 | [7d360fface60](https://github.com/tldr-pages/tldr/commit/7d360fface60422c2141e51c9f7b490fa0a3e88c)

