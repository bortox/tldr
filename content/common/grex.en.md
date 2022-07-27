---
author: ['NanthR', 'bl-ue', 'marchersimon']
date: 1621541621
title: "grex, TLDR Pages"
description: "grex, Simple command-line tool to generate regular expressions."
categories: "common"
---
> More information: <https://github.com/pemistahl/grex>.

- Generate a simple regular expression:

```bash
 grex space_separated_strings
```

- Generate a case-insensitive regular expression:

```bash
grex -i space_separated_strings
```

- Replace digits with '\d':

```bash
grex -d space_separated_strings
```

- Replace Unicode word character with '\w':

```bash
grex -w space_separated_strings
```

- Replace spaces with '\s':

```bash
grex -s space_separated_strings
```

- Add {min, max} quantifier representation for repeating sub-strings:

```bash
grex -r space_separated_strings
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | *: fix typos reported by Hunspell (#5848) Co-authored-by: marchersimon <50295997+marchersimon@users.noreply.github.com> Co-authored- [...] | 2021-05-20T22:13:41 | [8ebd171d6f00](https://github.com/tldr-pages/tldr/commit/8ebd171d6f001698709fefc02b1fd5cc9f3a99c4)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | multiple pages: normalize `regular expression` instead of `regex`, `regexp` or `pattern` (#5830) | 2021-05-10T11:03:12 | [10728f1ab485](https://github.com/tldr-pages/tldr/commit/10728f1ab485957d66af3940a030b0fb77611fc0)
[NanthR](mailto:61490162+NanthR@users.noreply.github.com) | grex: add command (#4396) | 2020-10-02T21:26:46 | [8b6b51b15f22](https://github.com/tldr-pages/tldr/commit/8b6b51b15f2223994a4c25e4e30b612a9f292de0)

