---
author: ['Stig124', 'Alex']
date: 1625841955
title: "fcrackzip, TLDR Pages"
description: "fcrackzip, ZIP archive password cracking utility."
categories: "linux"
---
> More information: <https://manned.org/fcrackzip>.

- Brute-force a password with a length of 4 to 8 characters, and contains only alphanumeric characters (order matters):

```bash
fcrackzip --brute-force --length 4-8 --charset aA1 archive
```

- Brute-force a password in verbose mode with a length of 3 characters that only contains lowercase characters, `$` and `%`:

```bash
fcrackzip -v --brute-force --length 3 --charset a:$% archive
```

- Brute-force a password that contains only lowercase and special characters:

```bash
fcrackzip --brute-force --length 4 --charset a! archive
```

- Brute-force a password containing only digits, starting from the password `12345`:

```bash
fcrackzip --brute-force --length 5 --charset 1 --init-password 12345 archive
```

- Crack a password using a wordlist:

```bash
fcrackzip --use-unzip --dictionary --init-password wordlist archive
```

- Benchmark cracking performance:

```bash
fcrackzip --benchmark
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Stig124](mailto:stigpro@outlook.fr) | linux/[a-g]: add more information link (#6076) | 2021-07-09T16:45:55 | [3697c62b5e5c](https://github.com/tldr-pages/tldr/commit/3697c62b5e5cd9bae7a99c591cb81d1ddcfbf792)
[Alex](mailto:alexandre.dhondt@gmail.com) | fcrackzip: add page (#3082) | 2019-06-09T01:43:09 | [14eabab0a64b](https://github.com/tldr-pages/tldr/commit/14eabab0a64bd7dbbbcfcb3f4cdb37c39639653b)

