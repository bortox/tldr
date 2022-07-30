---
author: ['BonfaceKilz', 'bl-ue', 'marchersimon']
date: 1620637392
title: "recsel"
description: "recsel, Print records from a recfile: a human-editable, plain text database."
categories: "common"
---
> More information: <https://www.gnu.org/software/recutils/manual/recutils.html>.

- Extract name and version field:

```bash
recsel -p name,version data.rec
```

- Use "~" to match a string with a given regular expression:

```bash
recsel -e "field_name ~ 'regular_expression' data.rec"
```

- Use a predicate to match a name and a version:

```bash
recsel -e "name ~ 'regular_expression' && version ~ 'regular_expression'" data.rec
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | multiple pages: normalize `regular expression` instead of `regex`, `regexp` or `pattern` (#5830) | 2021-05-10T11:03:12 | [10728f1ab485](https://github.com/tldr-pages/tldr/commit/10728f1ab485957d66af3940a030b0fb77611fc0)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | *: trim multiple spaces, fix line endings | 2021-04-04T01:44:24 | [04dd546e2de7](https://github.com/tldr-pages/tldr/commit/04dd546e2de7f59f40a867acca6f46b0dc8ea9b4)
[BonfaceKilz](mailto:bonfacemunyoki@gmail.com) | recsel: add page (#4309) | 2020-09-11T01:06:54 | [bcd66b20d4a6](https://github.com/tldr-pages/tldr/commit/bcd66b20d4a6f149eafdb579c7e5bfea94311756)

