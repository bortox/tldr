---
author: ['bl-ue', 'Stacey Adams']
date: 1621541621
title: "indent"
description: "indent, Change the appearance of a C/C++ program by inserting or deleting whitespace."
categories: "common"
---
> More information: <https://www.gnu.org/software/indent/>.

- Format C/C++ source according to the Linux style guide, automatically back up the original files, and replace with the indented versions:

```bash
indent --linux-style path/to/source.c path/to/another_source.c
```

- Format C/C++ source according to the GNU style, saving the indented version to a different file:

```bash
indent --gnu-style path/to/source.c -o path/to/indented_source.c
```

- Format C/C++ source according to the style of Kernighan & Ritchie (K&R), no tabs, 3 spaces per indent, and wrap lines at 120 characters:

```bash
indent --k-and-r-style --indent-level3 --no-tabs --line-length120 path/to/source.c -o path/to/indented_source.c
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | *: fix typos reported by Hunspell (#5848) Co-authored-by: marchersimon <50295997+marchersimon@users.noreply.github.com> Co-authored- [...] | 2021-05-20T22:13:41 | [8ebd171d6f00](https://github.com/tldr-pages/tldr/commit/8ebd171d6f001698709fefc02b1fd5cc9f3a99c4)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | *: trim multiple spaces, fix line endings | 2021-04-04T01:44:24 | [04dd546e2de7](https://github.com/tldr-pages/tldr/commit/04dd546e2de7f59f40a867acca6f46b0dc8ea9b4)
[Stacey Adams](mailto:stacey.belle.rose@gmail.com) | indent: add page (#4443) | 2020-10-05T16:21:23 | [e50c77099507](https://github.com/tldr-pages/tldr/commit/e50c770995079eeee14f588871f3dc5f83dce8fd)

