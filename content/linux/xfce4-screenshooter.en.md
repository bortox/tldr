---
author: ['Marco Bonelli', 'Lucas Gabriel Schneider', 'marchersimon']
date: 1622480790
title: "xfce4-screenshooter"
description: "xfce4-screenshooter, The XFCE4 screenshot tool."
categories: "linux"
---
> More information: <https://docs.xfce.org/apps/xfce4-screenshooter/start>.

- Launch the screenshooter GUI:

```bash
xfce4-screenshooter
```

- Take a screenshot of the entire screen and launch the GUI to ask how to proceed:

```bash
xfce4-screenshooter --fullscreen
```

- Take a screenshot of the entire screen and save it in the specified directory:

```bash
xfce4-screenshooter --fullscreen --save path/to/directory
```

- Wait some time before taking the screenshot:

```bash
xfce4-screenshooter --delay seconds
```

- Take a screenshot of a region of the screen (select using the mouse):

```bash
xfce4-screenshooter --region
```

- Take a screenshot of the active window, and copy it to the clipboard:

```bash
xfce4-screenshooter --window --clipboard
```

- Take a screenshot of the active window, and open it with a chosen program:

```bash
xfce4-screenshooter --window --open gimp
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | xfce4-screenshooter, xfce4-terminal: add link (#6075) | 2021-05-31T19:06:30 | [cfd0b5bd34da](https://github.com/tldr-pages/tldr/commit/cfd0b5bd34da972d7780b0b8580b3fb2af145607)
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | multiple pages: fixed typos (#2871) | 2019-04-06T14:34:03 | [9abddffd09d3](https://github.com/tldr-pages/tldr/commit/9abddffd09d33dba8c1e022085f7aa4e7ca6ce1b)
[Marco Bonelli](mailto:mebeim@users.noreply.github.com) | xfce4-screenshooter: add page (#2734) | 2019-01-29T12:05:47 | [c90ed14a96b6](https://github.com/tldr-pages/tldr/commit/c90ed14a96b610e7ca4898a69bd5a8d7e75bd9ec)

