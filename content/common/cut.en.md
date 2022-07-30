---
author: ['Waldir Pimenta', 'Dario Vladović', 'Emily Grace Seville', 'Lucas Gabriel Schneider', 'Petrus Kiendys', 'Marshall Yount', 'Starbeamrainbowlabs', 'Ruben Vereecken', 'Romain Prieto', 'marchersimon']
date: 1656268625
title: "cut"
description: "cut, Cut out fields from stdin or files."
categories: "common"
---
> More information: <https://www.gnu.org/software/coreutils/cut>.

- Print a specific character/field range of each line:

```bash
command | cut --characters|fields=1|1,10|1-10|1-|-10
```

- Print a range of each line with a specific delimiter:

```bash
command | cut --delimiter="," --characters=1
```

- Print a range of each line of the specific file:

```bash
cut --characters=1 path/to/file
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Emily Grace Seville](mailto:emilyseville7cf@gmail.com) | cut: refresh and add page (#7930) | 2022-06-26T20:37:05 | [4b9caaea845c](https://github.com/tldr-pages/tldr/commit/4b9caaea845c29381df6db051f98548c73b9e85c)
[Dario Vladović](mailto:d.vladimyr@gmail.com) | coreutils*: use short more info links (#5658) | 2021-04-01T17:54:26 | [4830093903f6](https://github.com/tldr-pages/tldr/commit/4830093903f66ccf3ebbc2ecf477286e45edac59)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | cut: add link (#5576) | 2021-03-30T13:39:27 | [f311aa47f394](https://github.com/tldr-pages/tldr/commit/f311aa47f394998f831ebd4af66733b85cc9c08a)
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | multiple pages: format technical tokens (#5119) Co-authored-by: bl-ue <54780737+bl-ue@users.noreply.github.com> Co-authored-by: [...] | 2021-01-31T18:05:18 | [a5fe31bc47ae](https://github.com/tldr-pages/tldr/commit/a5fe31bc47aece3efa5e66b52b3cf384f27d5d72)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | Harmonize formatting and capitalization of stdin/stdout/stderr | 2019-06-17T18:39:58 | [cf25745db1d8](https://github.com/tldr-pages/tldr/commit/cf25745db1d86744c762e15e6a2ba04ef9f9acc1)
[Petrus Kiendys](mailto:petrus.kiendys@dataductus.se) | cut: insert space between option and value, similar to previous examples | 2018-11-14T23:20:44 | [ec8a38ad6c77](https://github.com/tldr-pages/tldr/commit/ec8a38ad6c77e8cb219fc191df6798d2821d9a87)
[Starbeamrainbowlabs](mailto:sbrl@starbeamrainbowlabs.com) | cut: show syntax for n-to the end of a line (#2152) | 2018-06-23T13:07:17 | [fc3e1ecc5c05](https://github.com/tldr-pages/tldr/commit/fc3e1ecc5c059669607507eebd4a5d32f9e9bcf7)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | use the term "delimiter" for the -d option | 2016-05-07T19:28:06 | [2094ff365f27](https://github.com/tldr-pages/tldr/commit/2094ff365f2724deec8ace337b7b6c24dae80c55)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | cut: use a different separator characters | 2016-05-02T14:02:22 | [d1f217b68fc8](https://github.com/tldr-pages/tldr/commit/d1f217b68fc8ef7c73c4f3c3ad6877e3a3b02da8)
[Ruben Vereecken](mailto:rubenvereecken@gmail.com) | Formatted all pages according to guidelines. | 2016-01-08T09:38:59 | [066582e8eab5](https://github.com/tldr-pages/tldr/commit/066582e8eab57bce9861cc8d379e158d61f1cc95)
[Romain Prieto](mailto:choicesmade@gmail.com) | cut: fix token syntax + group by characters/fields | 2014-03-08T02:12:41 | [dfa4d6359786](https://github.com/tldr-pages/tldr/commit/dfa4d63597863d4366f8e7a98723315ee23878ab)
[Marshall Yount](mailto:marshall@yountlabs.com) | add support for cut command | 2014-03-07T18:43:18 | [52de7cfc4f94](https://github.com/tldr-pages/tldr/commit/52de7cfc4f942f436c028514eae1fd3178e5fc90)

