---
author: ['Howard Yun', 'Lucas Gabriel Schneider', 'Seth Falco']
date: 1629050349
title: "libreoffice"
description: "libreoffice, CLI for the powerful and free office suite LibreOffice."
categories: "linux"
---
> More information: <https://www.libreoffice.org/>.

- Open a space-separated list of files in read-only mode:

```bash
libreoffice --view path/to/file1 path/to/file2
```

- Display the content of specific files:

```bash
libreoffice --cat path/to/file1 path/to/file2
```

- Print files to a specific printer:

```bash
libreoffice --pt printer_name path/to/file1 path/to/file2
```

- Convert all `.doc` files in current directory to PDF:

```bash
libreoffice --convert-to pdf *.doc
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Seth Falco](mailto:seth@falco.fun) | *: fix errors reported by languagetool (#6069) | 2021-08-15T19:59:09 | [3e4c519004a4](https://github.com/tldr-pages/tldr/commit/3e4c519004a471c861cdc609fd7239ee3355671c)
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | multiple pages: format technical tokens (#5119) Co-authored-by: bl-ue <54780737+bl-ue@users.noreply.github.com> Co-authored-by: [...] | 2021-01-31T18:05:18 | [a5fe31bc47ae](https://github.com/tldr-pages/tldr/commit/a5fe31bc47aece3efa5e66b52b3cf384f27d5d72)
[Howard Yun](mailto:Haoy2001@gmail.com) | libreoffice: add page (#4489) | 2020-10-06T17:42:54 | [145785d4627d](https://github.com/tldr-pages/tldr/commit/145785d4627d406b604350e9145974c8d532a100)

