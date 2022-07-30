---
author: ['Schneider', 'Marco Bonelli', '85pando', 'bl-ue', 'Ruben Vereecken']
date: 1621541621
title: "calibre-server"
description: "calibre-server, A server application that can be used to distribute e-books over a network."
categories: "common"
---
> Note: e-books must already be imported into the library using the GUI or the `calibredb` CLI.

> More information: <https://manual.calibre-ebook.com/generated/en/calibre-server.html>.

- Start a server to distribute e-books. Access at http://localhost:8080:

```bash
calibre-server
```

- Start server on different port. Access at http://localhost:port:

```bash
calibre-server --port port
```

- Password protect the server:

```bash
calibre-server --username username --password password
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | *: fix typos reported by Hunspell (#5848) Co-authored-by: marchersimon <50295997+marchersimon@users.noreply.github.com> Co-authored- [...] | 2021-05-20T22:13:41 | [8ebd171d6f00](https://github.com/tldr-pages/tldr/commit/8ebd171d6f001698709fefc02b1fd5cc9f3a99c4)
[Marco Bonelli](mailto:marco@mebeim.net) | Refactor: reword English pages' links' descriptions. | 2019-06-03T14:19:41 | [66abb98ce935](https://github.com/tldr-pages/tldr/commit/66abb98ce935c0f4516bf30c4d6da72180d5a3ab)
[Schneider](mailto:lucas.schneider@sap.com) | calibre-server.md: add homepage | 2019-04-12T14:41:22 | [c77673a1c579](https://github.com/tldr-pages/tldr/commit/c77673a1c579835b568d2538a6b0a3d566787b7f)
[Ruben Vereecken](mailto:rubenvereecken@gmail.com) | Formatted all pages according to guidelines. | 2016-01-08T09:38:59 | [066582e8eab5](https://github.com/tldr-pages/tldr/commit/066582e8eab57bce9861cc8d379e158d61f1cc95)
[85pando](mailto:85pando@googlemail.com) | Add Calibre ebook library tools. | 2015-11-21T13:06:10 | [ddec78948539](https://github.com/tldr-pages/tldr/commit/ddec7894853983278e96154d8970a2097594414f)

