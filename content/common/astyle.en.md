---
author: ['Marco Bonelli', 'Frank Lamar', 'Schneider', 'marchersimon']
date: 1626166788
title: "astyle, TLDR Pages"
description: "astyle, Source code indenter, formatter, and beautifier for the C, C++, C# and Java programming languages."
categories: "common"
---
> Upon running, a copy of the original file is created with an ".orig" appended to the original file name.

> More information: <http://astyle.sourceforge.net/>.

- Apply the default style of 4 spaces per indent and no formatting changes:

```bash
astyle source_file
```

- Apply the Java style with attached braces:

```bash
astyle --style=java path/to/file
```

- Apply the allman style with broken braces:

```bash
astyle --style=allman path/to/file
```

- Apply a custom indent using spaces. Choose between 2 and 20 spaces:

```bash
astyle --indent=spaces=number_of_spaces path/to/file
```

- Apply a custom indent using tabs. Choose between 2 and 20 tabs:

```bash
astyle --indent=tab=number_of_tabs path/to/file
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: replace `java` with `Java` and `c++` with `C++` (#6224) | 2021-07-13T10:59:48 | [b615ea1e3495](https://github.com/tldr-pages/tldr/commit/b615ea1e34951c855e72470b73522ed0e0963d87)
[Marco Bonelli](mailto:marco@mebeim.net) | Refactor: reword English pages' links' descriptions. | 2019-06-03T14:19:41 | [66abb98ce935](https://github.com/tldr-pages/tldr/commit/66abb98ce935c0f4516bf30c4d6da72180d5a3ab)
[Schneider](mailto:lucas.schneider@sap.com) | astyle.md: add homepage | 2019-04-12T14:41:22 | [43d480740189](https://github.com/tldr-pages/tldr/commit/43d480740189f05eafa612484408d4ad77fc396a)
[Frank Lamar](mailto:lamar-frankie@users.noreply.github.com) | astyle: add page (#1543) | 2017-11-13T06:38:17 | [93f1fa439762](https://github.com/tldr-pages/tldr/commit/93f1fa4397624ce6e22c1eeba56e80ce7e3ebe60)

