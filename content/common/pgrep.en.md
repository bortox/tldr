---
author: ['lord63', 'bl-ue', 'Ruben Vereecken', 'Katy Moe', 'rprieto', 'Axel Navarro']
date: 1621541621
title: "pgrep, TLDR Pages"
description: "pgrep, Find or signal processes by name."
categories: "common"
---
> More information: <https://www.man7.org/linux/man-pages/man1/pkill.1.html>.

- Return PIDs of any running processes with a matching command string:

```bash
pgrep process_name
```

- Search for processes including their command-line options:

```bash
pgrep --full "process_name parameter"
```

- Search for processes run by a specific user:

```bash
pgrep --euid root process_name
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | *: fix typos reported by Hunspell (#5848) Co-authored-by: marchersimon <50295997+marchersimon@users.noreply.github.com> Co-authored- [...] | 2021-05-20T22:13:41 | [8ebd171d6f00](https://github.com/tldr-pages/tldr/commit/8ebd171d6f001698709fefc02b1fd5cc9f3a99c4)
[Axel Navarro](mailto:navarroaxel@gmail.com) | pgrep: add more info link (#5446) | 2021-03-15T19:29:40 | [160721def0ee](https://github.com/tldr-pages/tldr/commit/160721def0eeafb357f58bf8f16699ed44900b69)
[Ruben Vereecken](mailto:rubenvereecken@gmail.com) | Formatted all pages according to guidelines. | 2016-01-08T09:38:59 | [066582e8eab5](https://github.com/tldr-pages/tldr/commit/066582e8eab57bce9861cc8d379e158d61f1cc95)
[Katy Moe](mailto:katy@katy.moe) | pgrep: remove pkill example and correct tokens | 2016-01-02T15:50:53 | [ce9b0e1059f7](https://github.com/tldr-pages/tldr/commit/ce9b0e1059f71ab435a93c36888dce53678404ed)
[lord63](mailto:lord63.j@gmail.com) | Fix pgrep: remove the nonexistent -i parameter | 2015-10-31T08:46:42 | [bdeb134a92a9](https://github.com/tldr-pages/tldr/commit/bdeb134a92a9bc8876f547d6094fc766e1e6edca)
[lord63](mailto:lord63.j@gmail.com) | Fix lint for common | 2015-10-23T02:02:34 | [56a7cba6568f](https://github.com/tldr-pages/tldr/commit/56a7cba6568fcdaaeca2ddf0b80341cfc7de6285)
[rprieto](mailto:choicesmade@gmail.com) | Move pages back into a "pages" folder | 2014-03-04T13:28:29 | [f00bf64426a7](https://github.com/tldr-pages/tldr/commit/f00bf64426a792ee3aac792f9c0aec3f8b1eaa7d)

