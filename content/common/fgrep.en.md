---
author: ['Miles Glapa-Grossklag', 'César Soto Valero', 'bl-ue', 'marchersimon']
date: 1630501040
title: "fgrep, TLDR Pages"
description: "fgrep, Matches fixed strings in files."
categories: "common"
---
> Equivalent to `grep -F`.

> More information: <https://www.gnu.org/software/grep/manual/grep.html>.

- Search for an exact string in a file:

```bash
fgrep search_string path/to/file
```

- Search only lines that match entirely in files:

```bash
fgrep -x path/to/file1 path/to/file2
```

- Count the number of lines that match the given string in a file:

```bash
fgrep -c search_string path/to/file
```

- Show the line number in the file along with the line matched:

```bash
fgrep -n search_string path/to/file
```

- Display all lines except those that contain the search string:

```bash
fgrep -v search_string path/to/file
```

- Display filenames whose content matches the search string at least once:

```bash
fgrep -l search_string path/to/file1 path/to/file2
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Miles Glapa-Grossklag](mailto:miles@glapa-grossklag.com) | fgrep: remove incorrect use of 'regular expression' (#6427) | 2021-09-01T14:57:20 | [9d3781c32849](https://github.com/tldr-pages/tldr/commit/9d3781c3284966e3ac0cc3ca7b922c655d9b0405)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | multiple pages: normalize `regular expression` instead of `regex`, `regexp` or `pattern` (#5830) | 2021-05-10T11:03:12 | [10728f1ab485](https://github.com/tldr-pages/tldr/commit/10728f1ab485957d66af3940a030b0fb77611fc0)
[marchersimon](mailto:marchersimon@zohomail.eu) | add more information links | 2021-04-20T00:05:51 | [bc5d06ed1e1e](https://github.com/tldr-pages/tldr/commit/bc5d06ed1e1e112cfb368a38ae5918ef124cdc22)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | [many]: fix typos | 2020-12-11T22:27:28 | [2718393db1a3](https://github.com/tldr-pages/tldr/commit/2718393db1a358b04f94effb6a8b16e61647fb0b)
[César Soto Valero](mailto:cesarsotovalero@gmail.com) | fgrep: add page (#4001) | 2020-04-23T21:18:23 | [01e670afede6](https://github.com/tldr-pages/tldr/commit/01e670afede63c6fc63bcc1127c6c5f0d69623ff)

