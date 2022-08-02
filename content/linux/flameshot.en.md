---
author: ['Mehrad Mahmoudian', 'martín', 'Julien Tremblay McLellan - Library & Information Science', 'Matthew Peveler', 'Emily Grace Seville', 'Seth Falco']
date: 1659398121
title: "flameshot"
description: "flameshot, Screenshot utility with a GUI."
categories: "linux"
---
> Supports basic image editing, such as text, shapes, colors, and imgur.

> More information: <https://flameshot.org>.

- Create a fullscreen screenshot:

```bash
flameshot full
```

- Create a screenshot interactively:

```bash
flameshot gui
```

- Create a screenshot and save it to a specific path:

```bash
flameshot gui --path path/to/directory
```

- Create a screenshot interactively in a simplified mode:

```bash
flameshot launcher
```

- Create a screenshot from a specific monitor:

```bash
flameshot screen --number 2
```

- Create a screenshot and print it to the standard output:

```bash
flameshot gui --raw
```

- Create a screenshot and copy it to the clipboard:

```bash
flameshot gui --clipboard
```

- Create a screenshot with a specific delay in milliseconds:

```bash
flameshot full --delay 5000
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[martín](mailto:MartinCura@users.noreply.github.com) | fix(en/flameshot): delay should be milliseconds (#8276) | 2022-08-02T01:55:21 | [515e8473e841](https://github.com/tldr-pages/tldr/commit/515e8473e8416bb6af3b44f10fb05e6d766f830b)
[Emily Grace Seville](mailto:emilyseville7cf@gmail.com) | flameshot: refresh page (#8022) | 2022-05-16T14:35:38 | [cf51bfd7b82a](https://github.com/tldr-pages/tldr/commit/cf51bfd7b82aedf80d9cf82f9b7770ed036fa1c1)
[Mehrad Mahmoudian](mailto:m.mahmoudian@gmail.com) | flameshot: add examples and fix more info link (#6377) | 2021-08-17T14:43:01 | [381b52163f28](https://github.com/tldr-pages/tldr/commit/381b52163f284ef2fcabe68d607ffd6ae88f4df6)
[Seth Falco](mailto:seth@falco.fun) | *: fix errors reported by languagetool (#6069) | 2021-08-15T19:59:09 | [3e4c519004a4](https://github.com/tldr-pages/tldr/commit/3e4c519004a471c861cdc609fd7239ee3355671c)
[Matthew Peveler](mailto:matt.peveler@gmail.com) | flameshot: remove trailing space in title line Signed-off-by: Matthew Peveler <matt.peveler@gmail.com> | 2021-01-02T22:47:11 | [984219b45763](https://github.com/tldr-pages/tldr/commit/984219b457634b2a69bd47bc638ee8b73042b451)
[Julien Tremblay McLellan - Library & Information Science](mailto:jtremc@gmail.com) | flameshot: added page (#4324) | 2020-09-12T22:07:48 | [b5a3c99e17fb](https://github.com/tldr-pages/tldr/commit/b5a3c99e17fb4ac281f0b15b8757e2ea2a6bba5b)

