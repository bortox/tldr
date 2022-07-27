---
author: ['Diogo Pinela', 'meowmeowcat']
date: 1635858124
title: "screencapture, TLDR Pages"
description: "screencapture, Utility to take screenshots and screen recordings."
categories: "osx"
---
> More information: <https://ss64.com/osx/screencapture.html>.

- Take a screenshot and save it to a file:

```bash
screencapture path/to/file.png
```

- Take a screenshot including the mouse cursor:

```bash
screencapture -C path/to/file.png
```

- Take a screenshot and open it in Preview, instead of saving:

```bash
screencapture -P
```

- Take a screenshot of a selected rectangular area:

```bash
screencapture -i path/to/file.png
```

- Take a screenshot after a delay:

```bash
screencapture -T seconds path/to/file.png
```

- Make a screen recording and save it to a file:

```bash
screencapture -v path/to/file.mp4
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[meowmeowcat](mailto:meowmeowcat1211@gmail.com) | osascript, xattr, pmset, say, screencapture: add link (#7368) | 2021-11-02T14:02:04 | [b85bc433fb19](https://github.com/tldr-pages/tldr/commit/b85bc433fb1916e6fd9b053f9db24284d11fc4e6)
[Diogo Pinela](mailto:diogoid7400@gmail.com) | screencapture: add page (#3390) | 2019-10-13T15:58:34 | [9b884a5be682](https://github.com/tldr-pages/tldr/commit/9b884a5be682e143edfd602f9ddc071bd6697a3f)

