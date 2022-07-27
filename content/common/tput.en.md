---
author: ['Jeef', 'Sadeed', 'Hayden Schiff']
date: 1635014706
title: "tput, TLDR Pages"
description: "tput, View and modify terminal settings and capabilities."
categories: "common"
---
> More information: <https://manned.org/tput>.

- Move the cursor to a screen location:

```bash
tput cup y_coordinate x_coordinate
```

- Set foreground (af) or background (ab) color:

```bash
tput setaf|setab ansi_color_code
```

- Show number of columns, lines, or colors:

```bash
tput cols|lines|colors
```

- Ring the terminal bell:

```bash
tput bel
```

- Reset all terminal attributes:

```bash
tput sgr0
```

- Enable / Disable word wrap:

```bash
tput smam|rmam
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Sadeed](mailto:sadeeedw@gmail.com) | task, telnet, tldrl, tput, traceroute, transcode, type: add link (#7038) | 2021-10-23T20:45:06 | [81dc4a1e8016](https://github.com/tldr-pages/tldr/commit/81dc4a1e8016c5621134ebf80724be7d7d67c56a)
[Jeef](mailto:jeeftor@users.noreply.github.com) | tput: add two examples (#1299) | 2017-04-15T13:29:28 | [fdfa144cb01c](https://github.com/tldr-pages/tldr/commit/fdfa144cb01cd7b8c39f1fa68f21fc60e2046112)
[Hayden Schiff](mailto:oxguy3@gmail.com) | tput: add page | 2016-02-23T01:31:30 | [31a65a934818](https://github.com/tldr-pages/tldr/commit/31a65a934818b53a14c247b4fcdb2d623acc9fab)

