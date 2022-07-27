---
author: ['marchersimon']
date: 1658004747
title: "calc, TLDR Pages"
description: "calc, An interactive arbitrary-precision calculator in the terminal."
categories: "common"
---
> More information: <https://github.com/lcn2/calc>.

- Start `calc` in interactive mode:

```bash
calc
```

- Perform a calculation in non-interactive mode:

```bash
calc '85 * (36 / 4)'
```

- Perform a calculation without any output formatting (for use with pipes):

```bash
calc -p '4/3 * pi() * 5^3'
```

- Perform a calculation and then switch to [i]nteractive mode:

```bash
calc -i 'sqrt(2)'
```

- Start `calc` in a specific permission [m]ode (0 to 7, defaults to 7):

```bash
calc -m mode
```

- View an introduction to `calc`:

```bash
calc help intro
```

- View an overview of `calc`:

```bash
calc help overview
```

- Open the `calc` manual:

```bash
calc help
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | calc: set help example as lastest example (#8149) | 2022-07-16T22:52:27 | [0039248eb45e](https://github.com/tldr-pages/tldr/commit/0039248eb45ef45c6958e46670eea043225f83e4)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | calc: move from `linux` to `common` (#8148) | 2022-06-25T07:10:35 | [829a51b02447](https://github.com/tldr-pages/tldr/commit/829a51b024474aa484e033c7707f84058a5166e3)

