---
author: ['Ruben Vereecken', 'Dario Vladović', 'Jose Ricardo Ziviani', 'Guido Lena Cota', 'bl-ue', 'marchersimon']
date: 1621541621
title: "printf, TLDR Pages"
description: "printf, Format and print text."
categories: "common"
---
> More information: <https://www.gnu.org/software/coreutils/printf>.

- Print a text message:

```bash
printf "%s\n" "Hello world"
```

- Print an integer in bold blue:

```bash
printf "\e[1;34m%.3d\e[0m\n" 42
```

- Print a float number with the Unicode Euro sign:

```bash
printf "\u20AC %.2f\n" 123.4
```

- Print a text message composed with environment variables:

```bash
printf "var1: %s\tvar2: %s\n" "$VAR1" "$VAR2"
```

- Store a formatted message in a variable (does not work on zsh):

```bash
printf -v myvar "This is %s = %d\n" "a year" 2016
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | *: fix typos reported by Hunspell (#5848) Co-authored-by: marchersimon <50295997+marchersimon@users.noreply.github.com> Co-authored- [...] | 2021-05-20T22:13:41 | [8ebd171d6f00](https://github.com/tldr-pages/tldr/commit/8ebd171d6f001698709fefc02b1fd5cc9f3a99c4)
[Dario Vladović](mailto:d.vladimyr@gmail.com) | coreutils*: use short more info links (#5658) | 2021-04-01T17:54:26 | [4830093903f6](https://github.com/tldr-pages/tldr/commit/4830093903f66ccf3ebbc2ecf477286e45edac59)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | printf: add more information link (#5621) | 2021-03-30T16:11:55 | [ccb98be9e472](https://github.com/tldr-pages/tldr/commit/ccb98be9e472fdd27cd3494a237bacaa1d27ae5b)
[Guido Lena Cota](mailto:guido.lenacota@kreuzwerker.de) | Bulk change: move double quotes outside tokens (#4431) | 2020-10-04T19:33:38 | [354d4b8748ee](https://github.com/tldr-pages/tldr/commit/354d4b8748ee58813dd6830ced7c3b11067255d7)
[Ruben Vereecken](mailto:rubenvereecken@gmail.com) | Formatted all pages according to guidelines. | 2016-01-08T09:38:59 | [066582e8eab5](https://github.com/tldr-pages/tldr/commit/066582e8eab57bce9861cc8d379e158d61f1cc95)
[Jose Ricardo Ziviani](mailto:joserz@linux.vnet.ibm.com) | Add a new page about the printf command - printf is a bash command that acts like C's printf, supporting format strings and modifiers. [...] | 2015-12-28T22:07:49 | [395e8eaa54f7](https://github.com/tldr-pages/tldr/commit/395e8eaa54f73e652d0d408f8babf7cd7c85248b)

