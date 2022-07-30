---
author: ['Michael Bemmerl', 'Raghu Kalluri', 'Dario Vladović', 'Emily Grace Seville', 'Agniva De Sarker', 'Ruben Vereecken', 'marchersimon']
date: 1652466593
title: "tac"
description: "tac, Display and concatenate files with lines in reversed order."
categories: "common"
---
> See also: `cat`.

> More information: <https://www.gnu.org/software/coreutils/tac>.

- Concatenate specific files in reversed order:

```bash
tac path/to/file1 path/to/file2 ...
```

- Display `stdin` in reversed order:

```bash
cat path/to/file | tac
```

- Use a specific [s]eparator:

```bash
tac -s separator path/to/file1 path/to/file2 ...
```

- Use a specific [r]egex as a [s]eparator:

```bash
tac -r -s separator path/to/file1 path/to/file2 ...
```

- Use a separator [b]efore each file:

```bash
tac -b path/to/file1 path/to/file2 ...
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Emily Grace Seville](mailto:emilyseville7cf@gmail.com) | tac: refresh page (#8057) * More general descriptions and better title * Don't use `print` word * More specific verb in first sample [...] | 2022-05-13T20:29:53 | [e92c24d49dbd](https://github.com/tldr-pages/tldr/commit/e92c24d49dbde6bba88973727cc44e222afb8334)
[Dario Vladović](mailto:d.vladimyr@gmail.com) | coreutils*: use short more info links (#5658) | 2021-04-01T17:54:26 | [4830093903f6](https://github.com/tldr-pages/tldr/commit/4830093903f66ccf3ebbc2ecf477286e45edac59)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | tac: add link (#5594) | 2021-03-30T15:55:44 | [11cc51e1b98b](https://github.com/tldr-pages/tldr/commit/11cc51e1b98b85336f9ac2400dae49d653eb5ed7)
[Raghu Kalluri](mailto:raghu1kalluri@gmail.com) | tac: add stdin example (#3844) | 2020-02-08T15:48:47 | [2c9b7c9f5c2f](https://github.com/tldr-pages/tldr/commit/2c9b7c9f5c2f9b18a9f4d1c6a02b5d8a6c5561e9)
[Agniva De Sarker](mailto:agnivade@yahoo.co.in) | Applying the snake_case convention throughout the repo (#967) * Applying the snake_case convention throughout the repo - Also removing [...] | 2016-07-22T22:24:06 | [3da76e4150b8](https://github.com/tldr-pages/tldr/commit/3da76e4150b8631fd74aabfcc953cc23731b6bb8)
[Ruben Vereecken](mailto:rubenvereecken@gmail.com) | Formatted all pages according to guidelines. | 2016-01-08T09:38:59 | [066582e8eab5](https://github.com/tldr-pages/tldr/commit/066582e8eab57bce9861cc8d379e158d61f1cc95)
[Michael Bemmerl](mailto:mail@mx-server.de) | Add page for 'tac'. | 2015-12-28T22:01:39 | [6ac40a5b1a90](https://github.com/tldr-pages/tldr/commit/6ac40a5b1a902d0c610413d7b6a4ebcd63726092)

