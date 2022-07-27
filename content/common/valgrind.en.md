---
author: ['Marco Bonelli', 'Owen Voke', 'Gabriel Totev']
date: 1559564381
title: "valgrind, TLDR Pages"
description: "valgrind, Wrapper for a set of expert tools for profiling, optimizing and debugging programs."
categories: "common"
---
> Commonly used tools include `memcheck`, `cachegrind`, `callgrind`, `massif`, `helgrind`, and `drd`.

> More information: <http://www.valgrind.org>.

- Use the (default) Memcheck tool to show a diagnostic of memory usage by `program`:

```bash
valgrind program
```

- Use Memcheck to report all possible memory leaks of `program` in full detail:

```bash
valgrind --leak-check=full --show-leak-kinds=all program
```

- Use the Cachegrind tool to profile and log CPU cache operations of `program`:

```bash
valgrind --tool=cachegrind program
```

- Use the Massif tool to profile and log heap memory and stack usage of `program`:

```bash
valgrind --tool=massif --stacks=yes program
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Marco Bonelli](mailto:marco@mebeim.net) | Refactor: reword English pages' links' descriptions. | 2019-06-03T14:19:41 | [66abb98ce935](https://github.com/tldr-pages/tldr/commit/66abb98ce935c0f4516bf30c4d6da72180d5a3ab)
[Owen Voke](mailto:owzie123@gmail.com) | multiple pages: add homepages (#3026) * zstd: add link to homepage * zsh: add link to homepage * zopflipng: add link to homepage * [...] | 2019-05-14T18:09:07 | [c4e95b92c42f](https://github.com/tldr-pages/tldr/commit/c4e95b92c42fe9fe8428c8d7c8cd5ad8d0bd1b0b)
[Gabriel Totev](mailto:gttotev8@gmail.com) | valgrind: add page (#1407) * valgrind: add page * valgrind: tweak Memcheck example Provide alternate, clearer syntax that functions [...] | 2017-06-12T14:07:22 | [bf37b88bab1f](https://github.com/tldr-pages/tldr/commit/bf37b88bab1f3e6eefa499f3637282f55bda5e39)

