---
author: ['Miles Glapa-Grossklag', 'Bos Eriko Reyes', 'fejx', 'Axel Navarro', 'Ikko Ashimine', 'Seth Falco', 'marchersimon']
date: 1630283910
title: "figlet"
description: "figlet, Generate ASCII banners from user input."
categories: "common"
---
> See also: `showfigfonts`.

> More information: <http://www.figlet.org/figlet-man.html>.

- Generate by directly inputting text:

```bash
figlet input_text
```

- Use a custom font file:

```bash
figlet input_text -f path/to/font_file.flf
```

- Use a font from the default font directory (the extension can be omitted):

```bash
figlet input_text -f font_filename
```

- Pipe command output through FIGlet:

```bash
command | figlet
```

- Show available FIGlet fonts:

```bash
showfigfonts optional_string_to_display
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Miles Glapa-Grossklag](mailto:miles@glapa-grossklag.com) | figlet: fix language mixup (#6438) | 2021-08-30T02:38:30 | [ff4f42a5d916](https://github.com/tldr-pages/tldr/commit/ff4f42a5d916056d4c2d30406e2300ca1c981ba5)
[Seth Falco](mailto:seth@falco.fun) | *: fix errors reported by languagetool (#6069) | 2021-08-15T19:59:09 | [3e4c519004a4](https://github.com/tldr-pages/tldr/commit/3e4c519004a471c861cdc609fd7239ee3355671c)
[Ikko Ashimine](mailto:eltociear@gmail.com) | fix typo in figlet.md (#6271) extention -> extension | 2021-07-28T16:13:33 | [4cf6b588dda0](https://github.com/tldr-pages/tldr/commit/4cf6b588dda014aecf31998b09018f01727e45ef)
[Axel Navarro](mailto:navarroaxel@gmail.com) | showfigfonts: add page (#6217) | 2021-07-14T21:31:29 | [d5f22be32686](https://github.com/tldr-pages/tldr/commit/d5f22be326869ae289a49499fba5d5a11422bc96)
[marchersimon](mailto:marchersimon@zohomail.eu) | add more information links | 2021-04-20T00:05:51 | [bc5d06ed1e1e](https://github.com/tldr-pages/tldr/commit/bc5d06ed1e1e112cfb368a38ae5918ef124cdc22)
[fejx](mailto:florian.jhn@gmail.com) | Change all occurrences of file_name to filename (#4059) | 2020-05-22T14:31:24 | [4e1662b729ba](https://github.com/tldr-pages/tldr/commit/4e1662b729ba2bc23f7c12f606d41a86a613f8ea)
[Bos Eriko Reyes](mailto:bos.eriko@gmail.com) | move figlet to common pages (#3858) | 2020-02-16T07:57:45 | [0fdec2d3bcd1](https://github.com/tldr-pages/tldr/commit/0fdec2d3bcd12e2d5b256e7784a5782bfb1ddb59)

