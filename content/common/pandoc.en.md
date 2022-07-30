---
author: ['Waldir Pimenta', 'kalebo', 'pxgamer', 'Adrian Sieber', 'Matt Broberg', 'Seth Falco', 'Ruben Vereecken']
date: 1629050349
title: "pandoc"
description: "pandoc, Convert documents between various formats."
categories: "common"
---
> More information: <https://pandoc.org>.

- Convert file to PDF (the output format is determined by file extension):

```bash
pandoc input.md -o output.pdf
```

- Force conversion to use a specific format:

```bash
pandoc input.docx --to gfm -o output.md
```

- Convert to a standalone file with the appropriate headers/footers (for LaTeX, HTML, etc.):

```bash
pandoc input.md -s -o output.tex
```

- List all supported input formats:

```bash
pandoc --list-input-formats
```

- List all supported output formats:

```bash
pandoc --list-output-formats
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Seth Falco](mailto:seth@falco.fun) | *: fix errors reported by languagetool (#6069) | 2021-08-15T19:59:09 | [3e4c519004a4](https://github.com/tldr-pages/tldr/commit/3e4c519004a471c861cdc609fd7239ee3355671c)
[Matt Broberg](mailto:1744971+mbbroberg@users.noreply.github.com) | pandoc: update markdown example (#3521) Updating based on warning from Pandoc: `[WARNING] Deprecated: markdown_github. Use gfm instead.` | 2019-11-01T00:30:01 | [224243de5637](https://github.com/tldr-pages/tldr/commit/224243de5637417cff3829c513aee7c16bba2a8a)
[pxgamer](mailto:owzie123@gmail.com) | pandoc: add link to homepage | 2019-06-04T21:29:40 | [384086a8b4f2](https://github.com/tldr-pages/tldr/commit/384086a8b4f230649b5b4a735da7fbb5e8dcee18)
[kalebo](mailto:kaleb.olson@gmail.com) | pandoc: add example (#2483) | 2018-10-25T00:46:08 | [bfc713630f72](https://github.com/tldr-pages/tldr/commit/bfc713630f72897ebe43defbd6e9b6f58511da37)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | pandoc: update for v1.18 piping --help to the head command, as mentioned in #1072, isn't necessary anymore (in fact, doing that [...] | 2016-11-09T14:00:29 | [85395120d6bc](https://github.com/tldr-pages/tldr/commit/85395120d6bcb525c66f7199899d05fe84a57bbc)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | pandoc: improve desc, add 2 examples (#1072) The list of supported formats needs to be done this way until [...] | 2016-11-09T12:24:52 | [ca490f9fc9b3](https://github.com/tldr-pages/tldr/commit/ca490f9fc9b34d2b48b4f94e3997cb74eaf39f21)
[Ruben Vereecken](mailto:rubenvereecken@gmail.com) | Formatted all pages according to guidelines. | 2016-01-08T09:38:59 | [066582e8eab5](https://github.com/tldr-pages/tldr/commit/066582e8eab57bce9861cc8d379e158d61f1cc95)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | Changes to pandoc as discussed in #322 | 2015-11-25T08:51:55 | [c79e66aeceff](https://github.com/tldr-pages/tldr/commit/c79e66aeceff74b62c740775cd7074b4e85ed74b)
[Adrian Sieber](mailto:mail@adriansieber.com) | Add pandoc | 2015-11-09T13:52:05 | [8f48ee1d620d](https://github.com/tldr-pages/tldr/commit/8f48ee1d620d5d66f91a853fdeba1281cc76edfc)

