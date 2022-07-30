---
author: ['Agniva De Sarker', 'Schneider', 'Lucas Gabriel Schneider', 'Marco Bonelli', 'danieldc']
date: 1612112718
title: "godoc"
description: "godoc, Show documentation for go packages."
categories: "common"
---
> More information: <https://godoc.org/>.

- Display help for package "fmt":

```bash
godoc fmt
```

- Display help for the function "Printf" of "fmt" package:

```bash
godoc fmt Printf
```

- Serve documentation as a web server on port 6060:

```bash
godoc -http=:6060
```

- Create an index file:

```bash
godoc -write_index -index_files=path/to/file
```

- Use the given index file to search the docs:

```bash
godoc -http=:6060 -index -index_files=path/to/file
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | multiple pages: format technical tokens (#5119) Co-authored-by: bl-ue <54780737+bl-ue@users.noreply.github.com> Co-authored-by: [...] | 2021-01-31T18:05:18 | [a5fe31bc47ae](https://github.com/tldr-pages/tldr/commit/a5fe31bc47aece3efa5e66b52b3cf384f27d5d72)
[Marco Bonelli](mailto:marco@mebeim.net) | Refactor: reword English pages' links' descriptions. | 2019-06-03T14:19:41 | [66abb98ce935](https://github.com/tldr-pages/tldr/commit/66abb98ce935c0f4516bf30c4d6da72180d5a3ab)
[Schneider](mailto:lucas.schneider@sap.com) | godoc.md add homepage | 2019-04-11T09:49:15 | [7596715d28f3](https://github.com/tldr-pages/tldr/commit/7596715d28f3da38f8c39b705cb0cfb6f32216dc)
[Agniva De Sarker](mailto:agnivade@yahoo.co.in) | godoc: add options to use index (#2234) | 2018-08-20T18:31:17 | [c40a7761a182](https://github.com/tldr-pages/tldr/commit/c40a7761a182aefc1327805aa0e2ac7698374a31)
[danieldc](mailto:danieldc@users.noreply.github.com) | godoc: add page (#2170) | 2018-07-12T09:17:25 | [a1e93718c290](https://github.com/tldr-pages/tldr/commit/a1e93718c290ecebd04e2093b4416c822bddf4b7)

