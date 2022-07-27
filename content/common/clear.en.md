---
author: ['melgu', 'Iván', 'marchersimon']
date: 1618756407
title: "clear, TLDR Pages"
description: "clear, Clears the screen of the terminal."
categories: "common"
---
> More information: <https://manned.org/clear>.

- Clear the screen (equivalent to pressing Control-L in Bash shell):

```bash
clear
```

- Clear the screen but keep the terminal's scrollback buffer:

```bash
clear -x
```

- Indicate the type of terminal to clean (defaults to the value of the environment variable `TERM`):

```bash
clear -T type_of_terminal
```

- Show the version of `ncurses` used by `clear`:

```bash
clear -V
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[marchersimon](mailto:marchersimon@zohomail.eu) | replace `man.archlinux.org` with `manned.org` | 2021-04-18T16:33:27 | [9abb079afb69](https://github.com/tldr-pages/tldr/commit/9abb079afb6972f3de61a30e1b3fb849ad4b68d9)
[marchersimon](mailto:marchersimon@zohomail.eu) | clear: add link | 2021-04-18T16:33:27 | [907b82779088](https://github.com/tldr-pages/tldr/commit/907b827790882ee9086eb4d20cf8e3059343048a)
[Iván](mailto:ivan@ivanhercaz.com) | clear: add -x, -T and -V examples (#3684) Co-authored-by: Zlatan Vasović <zlatanvasovic@gmail.com> Co-authored-by: Starbeamrainbowlabs [...] | 2019-12-27T23:55:05 | [de1d2d2249dc](https://github.com/tldr-pages/tldr/commit/de1d2d2249dc67b2a914d229a6bed2af8a8343d9)
[melgu](mailto:mail@melvin-gundlach.de) | clear: Move to common/ (#2281) | 2018-09-03T20:03:32 | [3b0cdb58dccb](https://github.com/tldr-pages/tldr/commit/3b0cdb58dccb1c115057a3043a143b7e22413e84)

