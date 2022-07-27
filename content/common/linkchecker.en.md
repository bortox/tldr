---
author: ['Pierre Rudloff', 'bl-ue', 'marchersimon']
date: 1621541621
title: "linkchecker, TLDR Pages"
description: "linkchecker, Command-line client to check HTML documents and websites for broken links."
categories: "common"
---
> More information: <https://linkchecker.github.io/linkchecker/>.

- Find broken links on https://example.com/:

```bash
linkchecker https://example.com/
```

- Also check URLs that point to external domains:

```bash
linkchecker --check-extern https://example.com/
```

- Ignore URLs that match a specific regular expression:

```bash
linkchecker --ignore-url regular_expression https://example.com/
```

- Output results to a CSV file:

```bash
linkchecker --file-output csv/path/to/file https://example.com/
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | *: fix typos reported by Hunspell (#5848) Co-authored-by: marchersimon <50295997+marchersimon@users.noreply.github.com> Co-authored- [...] | 2021-05-20T22:13:41 | [8ebd171d6f00](https://github.com/tldr-pages/tldr/commit/8ebd171d6f001698709fefc02b1fd5cc9f3a99c4)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | multiple pages: normalize `regular expression` instead of `regex`, `regexp` or `pattern` (#5830) | 2021-05-10T11:03:12 | [10728f1ab485](https://github.com/tldr-pages/tldr/commit/10728f1ab485957d66af3940a030b0fb77611fc0)
[Pierre Rudloff](mailto:contact@rudloff.pro) | linkchecker: add page (#3611) | 2019-12-01T03:25:29 | [2130ae981dbc](https://github.com/tldr-pages/tldr/commit/2130ae981dbc68e39a4f6f8a0712404a00628d05)

