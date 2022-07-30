---
author: ['Seth Woodworth', 'Artem Szubowicz', 'pxgamer', 'Ryan Olson', 'Marco Bonelli', 'marchersimon', 'Ruben Vereecken']
date: 1623709650
title: "emacs"
description: "emacs, The extensible, customizable, self-documenting, real-time display editor."
categories: "common"
---
> See also `emacsclient`.

> More information: <https://www.gnu.org/software/emacs>.

- Start Emacs and open a file:

```bash
emacs path/to/file
```

- Open a file at a specified line number:

```bash
emacs +line_number path/to/file
```

- Start Emacs in console mode (without an X window):

```bash
emacs --no-window-system
```

- Start an Emacs server in the background (accessible via `emacsclient`):

```bash
emacs --daemon
```

- Stop a running Emacs server and all its instances, asking for confirmation on unsaved files:

```bash
emacsclient --eval '(save-buffers-kill-emacs)'
```

- Save a file in Emacs:

```bash
Ctrl + X, Ctrl + S
```

- Quit Emacs:

```bash
Ctrl + X, Ctrl + C
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | emacs, emacsclient: refresh (#6096) | 2021-06-15T00:27:30 | [68023b7eb89b](https://github.com/tldr-pages/tldr/commit/68023b7eb89b7a2897d19fb6ecad7fe6a1e96eb9)
[Ryan Olson](mailto:ryanolsonx@gmail.com) | emacs: open file at line number (#3780) | 2020-01-23T15:01:39 | [d17785495ddb](https://github.com/tldr-pages/tldr/commit/d17785495ddb25c8004c2129520a12311bb6682d)
[Marco Bonelli](mailto:mebeim@users.noreply.github.com) | emacs: clarify examples. (#3212) | 2019-07-31T05:25:48 | [c160121bdcea](https://github.com/tldr-pages/tldr/commit/c160121bdcea303dbaf956f1c7058d21926454b1)
[pxgamer](mailto:owzie123@gmail.com) | emacs: add link to homepage | 2019-06-09T06:54:24 | [5c0cc2cac11b](https://github.com/tldr-pages/tldr/commit/5c0cc2cac11b6eb671e659cfbd714885ee0f994a)
[Ruben Vereecken](mailto:rubenvereecken@gmail.com) | Formatted all pages according to guidelines. | 2016-01-08T09:38:59 | [066582e8eab5](https://github.com/tldr-pages/tldr/commit/066582e8eab57bce9861cc8d379e158d61f1cc95)
[Seth Woodworth](mailto:seth.ww@thelevelup.com) | adds emacs docs to quit and open file | 2015-12-30T17:55:36 | [e3c41d22ba0c](https://github.com/tldr-pages/tldr/commit/e3c41d22ba0c1717cc39f1ea774085e3a4880e40)
[Artem Szubowicz](mailto:shybovycha@gmail.com) | Started tldr for emacs | 2015-12-30T14:14:38 | [21c10a39e503](https://github.com/tldr-pages/tldr/commit/21c10a39e5036d5f4f8397b9905cc8c330ebebbc)

