---
author: ['Gregor Aisch', 'sabour_f', 'Miroslav Franc', 'Agniva De Sarker', 'Richard Mörbitz', 'Adrien Thebo', 'Starbeamrainbowlabs', 'Ruben Vereecken']
date: 1659034674
title: "make"
description: "make, Task runner for targets described in Makefile."
categories: "common"
---
> Mostly used to control the compilation of an executable from source code.

> More information: <https://www.gnu.org/software/make/manual/make.html>.

- Call the first target specified in the Makefile (usually named "all"):

```bash
make
```

- Call a specific target:

```bash
make target
```

- Call a specific target, executing 4 jobs at a time in parallel:

```bash
make -j4 target
```

- Use a specific Makefile:

```bash
make --file file
```

- Execute make from another directory:

```bash
make --directory directory
```

- Force making of a target, even if source files are unchanged:

```bash
make --always-make target
```

- Override a variable defined in the Makefile:

```bash
make target variable=new_value
```

- Override variables defined in the Makefile by the environment:

```bash
make --environment-overrides target
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Adrien Thebo](mailto:adrien@lagrange-automation.io) | make: add variable override example (#8249) | 2022-07-28T20:57:54 | [a81d36d37f9b](https://github.com/tldr-pages/tldr/commit/a81d36d37f9b7c6fd0f1f11ed8a27a84f02d989b)
[Richard Mörbitz](mailto:richard.moerbitz@tu-dresden.de) | make: add more information link | 2020-10-28T19:22:24 | [649bc40b2c23](https://github.com/tldr-pages/tldr/commit/649bc40b2c231bbea4a3383d66fd9d90b76ffe17)
[Richard Mörbitz](mailto:richard.moerbitz@tu-dresden.de) | make: add --environment-overrides example | 2020-10-28T19:22:24 | [ff24666e791b](https://github.com/tldr-pages/tldr/commit/ff24666e791bc6edce8368c41a101a2d83d0d237)
[Miroslav Franc](mailto:miroslav.franc@nic.cz) | GNU Make does not support -J | 2018-09-04T07:41:28 | [fd6904fb19fd](https://github.com/tldr-pages/tldr/commit/fd6904fb19fd45cd340c0d4761f527915d67c2d8)
[Starbeamrainbowlabs](mailto:sbrl@starbeamrainbowlabs.com) | Add multithreading example (#1398) | 2017-06-06T20:56:14 | [03d1622cfce5](https://github.com/tldr-pages/tldr/commit/03d1622cfce5c6a00a7371d0d32732bdc8db70e4)
[Agniva De Sarker](mailto:agnivade@yahoo.co.in) | make: Improve page - Fix syntax error - Expand flags - Change "rule" to "target" as its a better terminology for make | 2016-09-15T16:43:05 | [b18c728aceb6](https://github.com/tldr-pages/tldr/commit/b18c728aceb6a84fe5ef1df6f2fe271b4890e50d)
[Gregor Aisch](mailto:mail@driven-by-data.net) | added make -B | 2016-09-15T16:23:54 | [b256d9e49e08](https://github.com/tldr-pages/tldr/commit/b256d9e49e08ddf7807a3ab81c4514a2a5548b94)
[Ruben Vereecken](mailto:rubenvereecken@gmail.com) | Formatted all pages according to guidelines. | 2016-01-08T09:38:59 | [066582e8eab5](https://github.com/tldr-pages/tldr/commit/066582e8eab57bce9861cc8d379e158d61f1cc95)
[sabour_f](mailto:sabour_f@epitech.eu) | make: add page | 2016-01-04T12:59:09 | [1e936f5388e6](https://github.com/tldr-pages/tldr/commit/1e936f5388e6f4850d45b429e6f6d2653846e452)

