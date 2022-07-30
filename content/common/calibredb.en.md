---
author: ['Ein Verne', 'Schneider', 'Te-Chi Liu', 'Marco Bonelli', '85pando', 'bl-ue', 'Ruben Vereecken']
date: 1621541621
title: "calibredb"
description: "calibredb, Tool to manipulate the your e-book database."
categories: "common"
---
> Part of the Calibre e-book library.

> More information: <https://manual.calibre-ebook.com/generated/en/calibredb.html>.

- List e-books in the library with additional information:

```bash
calibredb list
```

- Search for e-books displaying additional information:

```bash
calibredb list --search search_term
```

- Search for just ids of e-books:

```bash
calibredb search search_term
```

- Add one or more e-books to the library:

```bash
calibredb add file1 file2 …
```

- Recursively add all e-books under a directory to the library:

```bash
calibredb add -r path/to/directory
```

- Remove one or more e-books from the library. You need the e-book IDs (see above):

```bash
calibredb remove id1 id2 …
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | *: fix typos reported by Hunspell (#5848) Co-authored-by: marchersimon <50295997+marchersimon@users.noreply.github.com> Co-authored- [...] | 2021-05-20T22:13:41 | [8ebd171d6f00](https://github.com/tldr-pages/tldr/commit/8ebd171d6f001698709fefc02b1fd5cc9f3a99c4)
[Ein Verne](mailto:einverne@gmail.com) | calibredb: add example (#3856) | 2020-02-17T03:30:04 | [b00ed9364b2a](https://github.com/tldr-pages/tldr/commit/b00ed9364b2a958bc08a941b125dae8ce7d66fe6)
[Marco Bonelli](mailto:marco@mebeim.net) | Refactor: reword English pages' links' descriptions. | 2019-06-03T14:19:41 | [66abb98ce935](https://github.com/tldr-pages/tldr/commit/66abb98ce935c0f4516bf30c4d6da72180d5a3ab)
[Schneider](mailto:lucas.schneider@sap.com) | calibredb.md: add homepage | 2019-04-12T14:41:22 | [20fd10c14af2](https://github.com/tldr-pages/tldr/commit/20fd10c14af28c98eb802b9ccadb3dc6f96d163e)
[Te-Chi Liu](mailto:liuderchi@gmail.com) | fixup: token string style (#1081) - use underscore rather than minus - use lower case rather than uppder case | 2016-09-21T17:35:46 | [5a54763c72d1](https://github.com/tldr-pages/tldr/commit/5a54763c72d1ed1b6eb5dbf195ee547527afc608)
[Ruben Vereecken](mailto:rubenvereecken@gmail.com) | Formatted all pages according to guidelines. | 2016-01-08T09:38:59 | [066582e8eab5](https://github.com/tldr-pages/tldr/commit/066582e8eab57bce9861cc8d379e158d61f1cc95)
[85pando](mailto:85pando@googlemail.com) | Update calibre-tools: missing backticks | 2015-11-24T14:38:13 | [4dfed291b331](https://github.com/tldr-pages/tldr/commit/4dfed291b33148c6c6a4201b555342488f73d0e5)
[85pando](mailto:85pando@users.noreply.github.com) | Update calibredb file/ids are not comma separated | 2015-11-24T12:01:45 | [9eaaaee4ac03](https://github.com/tldr-pages/tldr/commit/9eaaaee4ac03e82ce2269d2c388537f952339c6a)
[85pando](mailto:85pando@googlemail.com) | Add Calibre ebook library tools. | 2015-11-21T13:06:10 | [ddec78948539](https://github.com/tldr-pages/tldr/commit/ddec7894853983278e96154d8970a2097594414f)

