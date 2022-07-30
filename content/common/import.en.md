---
author: ['Waldir Pimenta', 'Jeef', 'Kyle', 'Seth Falco']
date: 1629747204
title: "import"
description: "import, Capture some or all of an X server screen, and save the image to a file."
categories: "common"
---
> Part of the ImageMagick library.

> More information: <https://imagemagick.org/script/import.php>.

- Capture the entire X server screen in the PostScript image format:

```bash
import -window root output.postscript
```

- Capture contents of a remote X server screen in the PNG format:

```bash
import -window root -display remote_host:screen.display output.png
```

- Capture a specific window, given its ID as displayed by `xwininfo`, into the JPEG format:

```bash
import -window window_id output.jpg
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Kyle](mailto:76597257+Gitleptune@users.noreply.github.com) | a*, g*, i*, osx[a*-i*]: add more information links (#6342) | 2021-08-23T21:33:24 | [0590a21917dc](https://github.com/tldr-pages/tldr/commit/0590a21917dc981d3cc64b8094b1cffa9d0a3b78)
[Seth Falco](mailto:seth@falco.fun) | *: fix errors reported by languagetool (#6069) | 2021-08-15T19:59:09 | [3e4c519004a4](https://github.com/tldr-pages/tldr/commit/3e4c519004a471c861cdc609fd7239ee3355671c)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | import: minor tweaks (#1322) | 2017-04-15T11:02:09 | [16969bf3dc4b](https://github.com/tldr-pages/tldr/commit/16969bf3dc4b1519bbd1db4d6dbd71b948a3134b)
[Jeef](mailto:jeeftor@users.noreply.github.com) | import: add page (#1255) | 2017-02-19T10:06:26 | [008080dc784b](https://github.com/tldr-pages/tldr/commit/008080dc784b35c7d482f15098cfcde698ba5875)

