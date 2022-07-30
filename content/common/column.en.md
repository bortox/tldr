---
author: ['Waldir Pimenta', 'kidpixo', 'Marco Bonelli', 'Seth Falco', 'marchersimon']
date: 1629050349
title: "column"
description: "column, Format standard input or a file into multiple columns."
categories: "common"
---
> Columns are filled before rows; the default separator is a whitespace.

> More information: <https://manned.org/column>.

- Format the output of a command for a 30 characters wide display:

```bash
printf "header1 header2\nbar foo\n" | column --output-width 30
```

- Split columns automatically and auto-align them in a tabular format:

```bash
printf "header1 header2\nbar foo\n" | column --table
```

- Specify the column delimiter character for the `--table` option (e.g. "," for CSV) (defaults to whitespace):

```bash
printf "header1,header2\nbar,foo\n" | column --table --separator ,
```

- Fill rows before filling columns:

```bash
printf "header1\nbar\nfoobar\n" | column --output-width 30 --fillrows
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Seth Falco](mailto:seth@falco.fun) | *: fix errors reported by languagetool (#6069) | 2021-08-15T19:59:09 | [3e4c519004a4](https://github.com/tldr-pages/tldr/commit/3e4c519004a471c861cdc609fd7239ee3355671c)
[marchersimon](mailto:marchersimon@zohomail.eu) | replace `man.archlinux.org` with `manned.org` | 2021-04-18T16:33:27 | [9abb079afb69](https://github.com/tldr-pages/tldr/commit/9abb079afb6972f3de61a30e1b3fb849ad4b68d9)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | Apply suggestion from code review Co-authored-by: bl-ue <54780737+bl-ue@users.noreply.github.com> | 2021-04-18T16:33:27 | [9dcb5e6fa0e3](https://github.com/tldr-pages/tldr/commit/9dcb5e6fa0e339633898360aa618e3cadbf23b7e)
[marchersimon](mailto:marchersimon@zohomail.eu) | column: add link | 2021-04-18T16:33:27 | [010ec036106c](https://github.com/tldr-pages/tldr/commit/010ec036106ce5c68aa2a9416ad819d1014178da)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | column: fix and reorder -s example (#2990) The `-s` option only works if `-t` is passed as well (as the description indicates), and [...] | 2019-05-16T22:46:41 | [0b77c6c5835b](https://github.com/tldr-pages/tldr/commit/0b77c6c5835b5c660fccf04873c6a1a3bd83ccfe)
[Marco Bonelli](mailto:mebeim@users.noreply.github.com) | column: fix typo (#2861) | 2019-04-02T12:14:39 | [9f2b387cbe57](https://github.com/tldr-pages/tldr/commit/9f2b387cbe5738db9d6b68fc2c7d775bfe703a45)
[kidpixo](mailto:kidpixo@gmail.com) | column: add page (#1053) | 2016-09-22T16:20:03 | [386a66cc9d13](https://github.com/tldr-pages/tldr/commit/386a66cc9d130ca4af845c5a3cfaa02f2cc781d9)

