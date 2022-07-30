---
author: ['Hayden Schiff', 'pxgamer', 'Guido Lena Cota', 'marchersimon']
date: 1620637392
title: "csvgrep"
description: "csvgrep, Filter CSV rows with string and pattern matching."
categories: "common"
---
> Included in csvkit.

> More information: <https://csvkit.readthedocs.io/en/latest/scripts/csvgrep.html>.

- Find rows that have a certain string in column 1:

```bash
csvgrep -c 1 -m string_to_match data.csv
```

- Find rows in which columns 3 or 4 match a certain regular expression:

```bash
csvgrep -c 3,4 -r regular_expression data.csv
```

- Find rows in which the "name" column does NOT include the string "John Doe":

```bash
csvgrep -i -c name -m "John Doe" data.csv
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | multiple pages: normalize `regular expression` instead of `regex`, `regexp` or `pattern` (#5830) | 2021-05-10T11:03:12 | [10728f1ab485](https://github.com/tldr-pages/tldr/commit/10728f1ab485957d66af3940a030b0fb77611fc0)
[Guido Lena Cota](mailto:guido.lenacota@kreuzwerker.de) | Bulk change: move double quotes outside tokens (#4431) | 2020-10-04T19:33:38 | [354d4b8748ee](https://github.com/tldr-pages/tldr/commit/354d4b8748ee58813dd6830ced7c3b11067255d7)
[pxgamer](mailto:owzie123@gmail.com) | csvgrep: add link to homepage | 2019-06-09T18:53:49 | [bdccb52b76b1](https://github.com/tldr-pages/tldr/commit/bdccb52b76b13477522d54b1fe2ee6a19cb3e8dc)
[Hayden Schiff](mailto:oxguy3@gmail.com) | csvgrep: grammatical fix | 2016-01-22T03:59:40 | [4ddf7488752c](https://github.com/tldr-pages/tldr/commit/4ddf7488752cf53a8026afbaf3f66b6e35ab4000)
[Hayden Schiff](mailto:oxguy3@gmail.com) | added csvgrep | 2016-01-22T00:03:29 | [588482fc7867](https://github.com/tldr-pages/tldr/commit/588482fc786707a73408dea06e285329b89296b5)

