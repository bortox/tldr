---
author: ['Dylan Rees', 'Enrique Matías Sánchez (Quique)', 'Enrique Matías Sánchez', 'marchersimon']
date: 1616676400
title: "halt, TLDR Pages"
description: "halt, Halt the system."
categories: "linux"
---
> More information: <https://www.man7.org/linux/man-pages/man8/halt.8.html>.

- Halt the system:

```bash
halt
```

- Power off the system (same as `poweroff`):

```bash
halt --poweroff
```

- Reboot the system (same as `reboot`):

```bash
halt --reboot
```

- Halt immediately without contacting the system manager:

```bash
halt --force --force
```

- Write the wtmp shutdown entry without halting the system:

```bash
halt --wtmp-only
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | poweroff, halt, reboot: add examples (#5485) | 2021-03-25T13:46:40 | [9330e542b36c](https://github.com/tldr-pages/tldr/commit/9330e542b36c5dfccb3ed24bb2c8cc15ade3715f)
[Enrique Matías Sánchez](mailto:cronopios@gmail.com) | halt: add link to its man page Co-authored-by: Axel Navarro <navarroaxel@gmail.com> | 2020-10-07T22:31:21 | [0a8d074a077f](https://github.com/tldr-pages/tldr/commit/0a8d074a077fdeab1bf835defc72cb598d9472fb)
[Enrique Matías Sánchez (Quique)](mailto:cronopios@gmail.com) | halt: add --poweroff example | 2020-10-07T22:31:21 | [422ef9fcd2a4](https://github.com/tldr-pages/tldr/commit/422ef9fcd2a4ce3ba2a50f4568029811e57909de)
[Dylan Rees](mailto:dylanrees@protonmail.ch) | Create halt.md | 2016-05-27T17:47:57 | [773e3f95fc9f](https://github.com/tldr-pages/tldr/commit/773e3f95fc9f2fa61381e900508f872a704eee2f)

