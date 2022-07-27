---
author: ['pixel', 'bl-ue', 'Owen Voke']
date: 1631455407
title: "cake, TLDR Pages"
description: "cake, The command-line processor for the CakePHP framework."
categories: "common"
---
> More information: <https://cakephp.org>.

- Display basic information about the current app and available commands:

```bash
cake
```

- Display a list of available routes:

```bash
cake routes
```

- Clear configuration caches:

```bash
cake cache clear_all
```

- Build the metadata cache:

```bash
cake schema_cache build --connection connection
```

- Clear the metadata cache:

```bash
cake schema_cache clear
```

- Clear a single cache table:

```bash
cake schema_cache clear table_name
```

- Start a development web server (defaults to port 8765):

```bash
cake server
```

- Start a REPL (interactive shell):

```bash
cake console
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[pixel](mailto:35269695+pixelcmtd@users.noreply.github.com) | pages/common/*.md: REPL Normalization (#6471) | 2021-09-12T16:03:27 | [882781e41019](https://github.com/tldr-pages/tldr/commit/882781e41019543fd716442e62faa1fb02d474b9)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | *: fix typos reported by Hunspell (#5848) Co-authored-by: marchersimon <50295997+marchersimon@users.noreply.github.com> Co-authored- [...] | 2021-05-20T22:13:41 | [8ebd171d6f00](https://github.com/tldr-pages/tldr/commit/8ebd171d6f001698709fefc02b1fd5cc9f3a99c4)
[Owen Voke](mailto:owzie123@gmail.com) | cake: add page (#3056) | 2019-05-28T19:50:04 | [58ea6b885305](https://github.com/tldr-pages/tldr/commit/58ea6b88530563078f8961305d3be989b4c05efe)

