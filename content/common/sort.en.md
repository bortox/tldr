---
author: ['Waldir Pimenta', 'Dario Vladović', 'Felix Yan', 'Larry850806', 'rprieto', 'lord63', 'Alexandre Bruyant', 'hntee', 'Thomas Wünsche', 'Ruben Vereecken', 'Eric Lee']
date: 1617292466
title: "sort"
description: "sort, Sort lines of text files."
categories: "common"
---
> More information: <https://www.gnu.org/software/coreutils/sort>.

- Sort a file in ascending order:

```bash
sort path/to/file
```

- Sort a file in descending order:

```bash
sort --reverse path/to/file
```

- Sort a file in case-insensitive way:

```bash
sort --ignore-case path/to/file
```

- Sort a file using numeric rather than alphabetic order:

```bash
sort --numeric-sort path/to/file
```

- Sort `/etc/passwd` by the 3rd field of each line numerically, using ":" as a field separator:

```bash
sort --field-separator=: --key=3n /etc/passwd
```

- Sort a file preserving only unique lines:

```bash
sort --unique path/to/file
```

- Sort a file, printing the output to the specified output file (can be used to sort a file in-place):

```bash
sort --output=path/to/file path/to/file
```

- Sort numbers with exponents:

```bash
sort --general-numeric-sort path/to/file
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Dario Vladović](mailto:d.vladimyr@gmail.com) | coreutils*: use short more info links (#5658) | 2021-04-01T17:54:26 | [4830093903f6](https://github.com/tldr-pages/tldr/commit/4830093903f66ccf3ebbc2ecf477286e45edac59)
[Alexandre Bruyant](mailto:alexandre.bruyant@gmail.com) | sort: expand short flags, improve field separator example (#5233) | 2021-02-09T15:56:54 | [78b959f6edde](https://github.com/tldr-pages/tldr/commit/78b959f6edde47fa31e1ef49c594439478b4961e)
[Thomas Wünsche](mailto:42999314+thomaswuensche@users.noreply.github.com) | sort: add output file example (#5040) | 2021-01-04T15:52:10 | [152ee9b622b1](https://github.com/tldr-pages/tldr/commit/152ee9b622b192cb151217ce3684c05ff898947f)
[hntee](mailto:ihntee@gmail.com) | sort: add --general-numeric-sort example (#4325) | 2020-09-09T12:33:24 | [04e4ac93ab50](https://github.com/tldr-pages/tldr/commit/04e4ac93ab500ce5e83b7584f91028199825fd13)
[Eric Lee](mailto:cslee@users.noreply.github.com) | sort: add --ignore-case example (#2611) | 2018-11-25T21:29:28 | [92295cac37f4](https://github.com/tldr-pages/tldr/commit/92295cac37f4b92b8c00a355db36c8947b6c6352)
[Felix Yan](mailto:felixonmars@archlinux.org) | coreutils commands: move pages to common/ folder (#2442) | 2018-10-16T19:29:50 | [72b4f22ff97b](https://github.com/tldr-pages/tldr/commit/72b4f22ff97b1890344f2af870ad3d1c89a3f0b5)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | sort: swap examples to introduce options gradually | 2016-05-10T15:12:37 | [8eadb597a6c7](https://github.com/tldr-pages/tldr/commit/8eadb597a6c768c0e27775ef408f926b55e2360e)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | sort.md: improve example descriptions | 2016-05-10T15:09:55 | [616f92d71947](https://github.com/tldr-pages/tldr/commit/616f92d719478f2f21ad4467b2af78eeddff9a0a)
[Larry850806](mailto:pudding850806@gmail.com) | Update sort.md | 2016-03-30T17:13:36 | [e608317d3c67](https://github.com/tldr-pages/tldr/commit/e608317d3c67a068f499030953993bcd5fb4488a)
[Ruben Vereecken](mailto:rubenvereecken@gmail.com) | Formatted all pages according to guidelines. | 2016-01-08T09:38:59 | [066582e8eab5](https://github.com/tldr-pages/tldr/commit/066582e8eab57bce9861cc8d379e158d61f1cc95)
[lord63](mailto:lord63.j@gmail.com) | Don't exclude markown md038 warning, close #314 also fix the md038 warning in common/sort.md | 2015-11-03T13:24:36 | [fbd8c639ffb5](https://github.com/tldr-pages/tldr/commit/fbd8c639ffb5012206148b1175424811e3ecb8ff)
[rprieto](mailto:choicesmade@gmail.com) | Move pages back into a "pages" folder | 2014-03-04T13:28:29 | [f00bf64426a7](https://github.com/tldr-pages/tldr/commit/f00bf64426a792ee3aac792f9c0aec3f8b1eaa7d)

