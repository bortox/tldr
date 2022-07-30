---
author: ['Waldir Pimenta', 'Emily Grace Seville', 'Δημήτρης Φιλίππου', 'bl-ue', 'Jeef', 'Seth Falco']
date: 1647882468
title: "xdotool"
description: "xdotool, Command-line automation for X11."
categories: "linux"
---
> More information: <https://manned.org/xdotool>.

- Retrieve the X-Windows window ID of the running Firefox window(s):

```bash
xdotool search --onlyvisible --name firefox
```

- Click the right mouse button:

```bash
xdotool click 3
```

- Get the ID of the currently active window:

```bash
xdotool getactivewindow
```

- Focus on the window with ID of 12345:

```bash
xdotool windowfocus --sync 12345
```

- Type a message, with a 500ms delay for each letter:

```bash
xdotool type --delay 500 "Hello world"
```

- Press the enter key:

```bash
xdotool key KP_Enter
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Emily Grace Seville](mailto:emilyseville7cf@gmail.com) | linux/*: add more information link (#7848) | 2022-03-21T18:07:48 | [4659bcb243ac](https://github.com/tldr-pages/tldr/commit/4659bcb243ac572c9e0c95117097801f1e62bda4)
[Seth Falco](mailto:seth@falco.fun) | *: fix errors reported by languagetool (#6069) | 2021-08-15T19:59:09 | [3e4c519004a4](https://github.com/tldr-pages/tldr/commit/3e4c519004a471c861cdc609fd7239ee3355671c)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | *: fix typos reported by Hunspell (#5848) Co-authored-by: marchersimon <50295997+marchersimon@users.noreply.github.com> Co-authored- [...] | 2021-05-20T22:13:41 | [8ebd171d6f00](https://github.com/tldr-pages/tldr/commit/8ebd171d6f001698709fefc02b1fd5cc9f3a99c4)
[Δημήτρης Φιλίππου](mailto:p3160253@dias.aueb.gr) | xdotool: added more examples (#1650) | 2017-11-26T10:47:45 | [d6e9cf00928c](https://github.com/tldr-pages/tldr/commit/d6e9cf00928c186d9a306d2e2fe59488731e6ec4)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | xdotool: fix typo | 2017-04-15T00:08:36 | [09837acac5c0](https://github.com/tldr-pages/tldr/commit/09837acac5c05d75bd5fd39602894b687bf1b52a)
[Jeef](mailto:jeeftor@users.noreply.github.com) | x11vnc, xdotool, rev: add pages (#1264) | 2017-02-21T04:52:56 | [8fdc908325c5](https://github.com/tldr-pages/tldr/commit/8fdc908325c52c333fc3652a3afd38a54cff21b7)

