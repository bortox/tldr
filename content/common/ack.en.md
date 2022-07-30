---
author: ['Irina', 'Morgan Evans', 'GermanS', 'Agniva De Sarker', 'Schneider', 'Cameron Tod', 'Srinivasan R', 'Marco Bonelli', 'bl-ue', 'Ruben Vereecken']
date: 1634106377
title: "ack"
description: "ack, A search tool like grep, optimized for developers."
categories: "common"
---
> See also: `rg`, which is much faster.

> More information: <https://beyondgrep.com/documentation>.

- Search for files containing a string or regular expression in the current directory recursively:

```bash
ack "search_pattern"
```

- Search for a case-insensitive pattern:

```bash
ack --ignore-case "search_pattern"
```

- Search for lines matching a pattern, printing [o]nly the matched text and not the rest of the line:

```bash
ack -o "search_pattern"
```

- Limit search to files of a specific type:

```bash
ack --type=ruby "search_pattern"
```

- Do not search in files of a specific type:

```bash
ack --type=noruby "search_pattern"
```

- Count the total number of matches found:

```bash
ack --count --no-filename "search_pattern"
```

- Print the file names and the number of matches for each file only:

```bash
ack --count --files-with-matches "search_pattern"
```

- List all the values that can be used with `--type`:

```bash
ack --help-types
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Irina](mailto:91758930+iridacea@users.noreply.github.com) | *: refresh Russian translation (#6850) | 2021-10-13T08:26:17 | [639b2e4e10c7](https://github.com/tldr-pages/tldr/commit/639b2e4e10c73c8014036c302192e4faa51e5279)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | ack: refresh (#5436) | 2021-03-25T00:50:01 | [045fee830cc3](https://github.com/tldr-pages/tldr/commit/045fee830cc3f880cb132495f481b2ea0456a836)
[GermanS](mailto:german.semenkov@gmail.com) | ack: fix typo (#4196) | 2020-07-16T23:33:06 | [ad248fb1170c](https://github.com/tldr-pages/tldr/commit/ad248fb1170c1bac38349a554cf3b37270747353)
[Cameron Tod](mailto:ctod@amazon.com) | ack: add regex, single file search examples (#4007) Co-authored-by: Zlatan Vasović <zlatanvasovic@gmail.com> Co-authored-by: [...] | 2020-05-11T10:57:08 | [2cffa0ccee2a](https://github.com/tldr-pages/tldr/commit/2cffa0ccee2a714e8e6be744c3021b84d722ec1c)
[Marco Bonelli](mailto:marco@mebeim.net) | Refactor: reword English pages' links' descriptions. | 2019-06-03T14:19:41 | [66abb98ce935](https://github.com/tldr-pages/tldr/commit/66abb98ce935c0f4516bf30c4d6da72180d5a3ab)
[Schneider](mailto:lucas.schneider@sap.com) | ack.md add homepage | 2019-04-11T09:49:15 | [6b873507126f](https://github.com/tldr-pages/tldr/commit/6b873507126f135bda674d3fabc40e61d9e8f2b4)
[Agniva De Sarker](mailto:agnivade@yahoo.co.in) | ack: made some changes - Changed description of file type - Added command to list all types | 2019-03-07T09:36:32 | [6cbf29d3fc42](https://github.com/tldr-pages/tldr/commit/6cbf29d3fc426e43d12c7c07226c014818ac93ac)
[Morgan Evans](mailto:negamorgan@gmail.com) | ack: clarify file types syntax meaning fix #2805 | 2019-03-07T09:36:32 | [851990873c09](https://github.com/tldr-pages/tldr/commit/851990873c090f58c1b34ebed886b2f8fe98965c)
[Ruben Vereecken](mailto:rubenvereecken@gmail.com) | Formatted all pages according to guidelines. | 2016-01-08T09:38:59 | [066582e8eab5](https://github.com/tldr-pages/tldr/commit/066582e8eab57bce9861cc8d379e158d61f1cc95)
[Srinivasan R](mailto:srinivasanr@gmail.com) | Normalize the final new line Fixes #310 Some files had no newlines, some had 1 newline and some more than 1 newline. Normalize them [...] | 2015-10-28T09:33:06 | [e4114fa6cce7](https://github.com/tldr-pages/tldr/commit/e4114fa6cce7339425809afef817b06e872d7ca7)
[Morgan Evans](mailto:morganrevans@gmail.com) | adding ack | 2014-10-02T00:02:25 | [5a82ba202f47](https://github.com/tldr-pages/tldr/commit/5a82ba202f47e9a439823a6a18b10fb2f0d37778)

