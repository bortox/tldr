---
author: ['kjwon15', 'Waldir Pimenta', 'Emily Grace Seville', 'Hugo Locurcio', 'Roshak Zarhoun', 'Jezeniel Zapanta', 'Seth Falco']
date: 1647882468
title: "xclip"
description: "xclip, X11 clipboard manipulation tool, similar to `xsel`."
categories: "linux"
---
> Handles the X primary and secondary selections, plus the system clipboard (`Ctrl + C`/`Ctrl + V`).

> More information: <https://manned.org/xclip>.

- Copy the output from a command to the X11 primary selection area (clipboard):

```bash
echo 123 | xclip
```

- Copy the output from a command to a given X11 selection area:

```bash
echo 123 | xclip -selection primary|secondary|clipboard
```

- Copy the output from a command to the system clipboard, using short notation:

```bash
echo 123 | xclip -sel clip
```

- Copy the contents of a file into the system clipboard:

```bash
xclip -sel clip input_file.txt
```

- Copy the contents of a PNG into the system clipboard (can be pasted in other programs correctly):

```bash
xclip -sel clip -t image/png input_file.png
```

- Copy the user input in the console into the system clipboard:

```bash
xclip -i
```

- Paste the contents of the X11 primary selection area to the console:

```bash
xclip -o
```

- Paste the contents of the system clipboard to the console:

```bash
xclip -o -sel clip
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Emily Grace Seville](mailto:emilyseville7cf@gmail.com) | linux/*: add more information link (#7848) | 2022-03-21T18:07:48 | [4659bcb243ac](https://github.com/tldr-pages/tldr/commit/4659bcb243ac572c9e0c95117097801f1e62bda4)
[Seth Falco](mailto:seth@falco.fun) | *: fix errors reported by languagetool (#6069) | 2021-08-15T19:59:09 | [3e4c519004a4](https://github.com/tldr-pages/tldr/commit/3e4c519004a471c861cdc609fd7239ee3355671c)
[Roshak Zarhoun](mailto:roshakz@gmail.com) | xclip: fix example description and replace 1 example (#4985) | 2020-11-27T20:10:03 | [d23dc34a258f](https://github.com/tldr-pages/tldr/commit/d23dc34a258f40b24ec5e1e993fb0364a2e32aa8)
[Hugo Locurcio](mailto:hugo.locurcio@hugo.pro) | xclip: add PNG image copying example (#3073) | 2019-06-02T14:09:10 | [aeef500f4a6a](https://github.com/tldr-pages/tldr/commit/aeef500f4a6a1b9353caea57d890617be1d71af0)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | xclip: expand page (#1494) | 2017-09-16T23:16:36 | [876e67faa9dc](https://github.com/tldr-pages/tldr/commit/876e67faa9dcdb0d9c72298878465a781aa202b8)
[Jezeniel Zapanta](mailto:jpzapanta22@gmail.com) | xclip: Fix whitespace | 2016-04-01T05:11:16 | [02bc948695c4](https://github.com/tldr-pages/tldr/commit/02bc948695c4d563232004b69c2c8a6de69324bd)
[Jezeniel Zapanta](mailto:jpzapanta22@gmail.com) | xclip:Add copy to system clipboard | 2016-03-29T03:22:33 | [aed9bab83127](https://github.com/tldr-pages/tldr/commit/aed9bab831271e33232469301169ab217c034e8e)
[kjwon15](mailto:kjwonmail@gmail.com) | xclip: add page | 2016-01-27T05:57:05 | [d79643b3a149](https://github.com/tldr-pages/tldr/commit/d79643b3a149788ad89166f594c25a5001b7cda0)

