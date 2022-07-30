---
author: ['Waldir Pimenta', 'Eddie Antonio Santos', 'Axel Navarro', 'lord63', 'kxy', 'marchersimon', 'Ruben Vereecken']
date: 1618756407
title: "ar"
description: "ar, Create, modify, and extract from archives (`.a`, `.so`, `.o`)."
categories: "common"
---
> More information: <https://manned.org/ar>.

- Extract all members from an archive:

```bash
ar -x path/to/file.a
```

- List the members of an archive:

```bash
ar -t path/to/file.a
```

- Replace or add files to an archive:

```bash
ar -r path/to/file.a path/to/file1.o path/to/file2.o
```

- Insert an object file index (equivalent to using `ranlib`):

```bash
ar -s path/to/file.a
```

- Create an archive with files and an accompanying object file index:

```bash
ar -rs path/to/file.a path/to/file1.o path/to/file2.o
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[marchersimon](mailto:marchersimon@zohomail.eu) | replace `man.archlinux.org` with `manned.org` | 2021-04-18T16:33:27 | [9abb079afb69](https://github.com/tldr-pages/tldr/commit/9abb079afb6972f3de61a30e1b3fb849ad4b68d9)
[Axel Navarro](mailto:navarroaxel@gmail.com) | Apply suggestions from code review | 2021-04-18T16:33:27 | [c62b624b171b](https://github.com/tldr-pages/tldr/commit/c62b624b171be9dc4cc24ebfa1fd369adb90474f)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | Apply suggestions from code review Co-authored-by: Axel Navarro <navarroaxel@gmail.com> | 2021-04-18T16:33:27 | [9eb612378634](https://github.com/tldr-pages/tldr/commit/9eb612378634ff548a7da6c44f106f5e4625a161)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | Apply suggestions from code review Co-authored-by: bl-ue <54780737+bl-ue@users.noreply.github.com> | 2021-04-18T16:33:27 | [3c2cf700535c](https://github.com/tldr-pages/tldr/commit/3c2cf700535c96240fc4832e5c1e117c6e4b696d)
[marchersimon](mailto:marchersimon@zohomail.eu) | ar: add link | 2021-04-18T16:33:27 | [bc1219f3c90d](https://github.com/tldr-pages/tldr/commit/bc1219f3c90dc2328626e04ab6496ddd8f0405d3)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | ar: add commas to list | 2016-09-29T14:31:04 | [76f211601ee2](https://github.com/tldr-pages/tldr/commit/76f211601ee25340ae6818f22c107596118262b2)
[Ruben Vereecken](mailto:rubenvereecken@gmail.com) | Formatted all pages according to guidelines. | 2016-01-08T09:38:59 | [066582e8eab5](https://github.com/tldr-pages/tldr/commit/066582e8eab57bce9861cc8d379e158d61f1cc95)
[Eddie Antonio Santos](mailto:easantos@ualberta.ca) | ar: add examples and clean-up | 2015-12-30T23:05:57 | [a4768ccd28e5](https://github.com/tldr-pages/tldr/commit/a4768ccd28e54efa495e0e11da1a3e9feef2abfc)
[lord63](mailto:lord63.j@gmail.com) | Fix lint for common | 2015-10-23T02:02:34 | [56a7cba6568f](https://github.com/tldr-pages/tldr/commit/56a7cba6568fcdaaeca2ddf0b80341cfc7de6285)
[kxy](mailto:kyrwastaken@gmail.com) | added ar.md | 2014-03-10T16:31:07 | [ffffef8db3c8](https://github.com/tldr-pages/tldr/commit/ffffef8db3c84f6cfabdd3a7278c8cc9b3be5414)

