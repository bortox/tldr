---
author: ['bl-ue', 'Ein Verne']
date: 1621541621
title: "googler, TLDR Pages"
description: "googler, Search Google from command-line."
categories: "common"
---
> More information: <https://github.com/jarun/googler>.

- Search Google for a keyword:

```bash
googler keyword
```

- Search Google and open the first result in web browser:

```bash
googler -j keyword
```

- Show N search results (default 10):

```bash
googler -n N keyword
```

- Disable automatic spelling correction:

```bash
googler -x keyword
```

- Search one site for a keyword:

```bash
googler -w site keyword
```

- Show Google search result in JSON format:

```bash
googler --json keyword
```

- Perform in-place self-upgrade:

```bash
googler -u
```

- For more help in interactive mode:

```bash
?
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | *: fix typos reported by Hunspell (#5848) Co-authored-by: marchersimon <50295997+marchersimon@users.noreply.github.com> Co-authored- [...] | 2021-05-20T22:13:41 | [8ebd171d6f00](https://github.com/tldr-pages/tldr/commit/8ebd171d6f001698709fefc02b1fd5cc9f3a99c4)
[Ein Verne](mailto:einverne@gmail.com) | googler: add page (#3531) | 2019-11-07T10:14:01 | [aeb623cbee51](https://github.com/tldr-pages/tldr/commit/aeb623cbee51458bfcbe87f8b3cfb3ba53139328)

