---
author: ['Jaseem Abid', 'pxgamer', 'vritser', 'bl-ue', 'marchersimon']
date: 1623709650
title: "emacsclient"
description: "emacsclient, Open files in an existing Emacs server."
categories: "common"
---
> See also `emacs`.

> More information: <https://www.emacswiki.org/emacs/EmacsClient>.

- Open a file in an existing Emacs server (using GUI if available):

```bash
emacsclient path/to/file
```

- Open a file in console mode (without an X window):

```bash
emacsclient --no-window-system path/to/file
```

- Open a file in a new Emacs window:

```bash
emacsclient --create-frame path/to/file
```

- Evaluate a command, printing the output to stdout, and then quit:

```bash
emacsclient --eval '(command)'
```

- Specify an alternative editor in case no Emacs server is running:

```bash
emacsclient --alternate-editor editor path/to/file
```

- Stop a running Emacs server and all its instances, asking for confirmation on unsaved files:

```bash
emacsclient --eval '(save-buffers-kill-emacs)'
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | emacs, emacsclient: refresh (#6096) | 2021-06-15T00:27:30 | [68023b7eb89b](https://github.com/tldr-pages/tldr/commit/68023b7eb89b7a2897d19fb6ecad7fe6a1e96eb9)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | *: fix typos reported by Hunspell (#5848) Co-authored-by: marchersimon <50295997+marchersimon@users.noreply.github.com> Co-authored- [...] | 2021-05-20T22:13:41 | [8ebd171d6f00](https://github.com/tldr-pages/tldr/commit/8ebd171d6f001698709fefc02b1fd5cc9f3a99c4)
[vritser](mailto:1429594204@qq.com) | emacsclient: add -c -e example (#4182) | 2020-07-17T22:17:43 | [f08dbe7da192](https://github.com/tldr-pages/tldr/commit/f08dbe7da19274c6ac1fbdbe35767f95f34fadea)
[pxgamer](mailto:owzie123@gmail.com) | emacsclient: add link to homepage | 2019-06-09T06:54:24 | [0c78bf06a506](https://github.com/tldr-pages/tldr/commit/0c78bf06a506745dbd169a57acc6298d623c9399)
[Jaseem Abid](mailto:jaseemabid@gmail.com) | emacsclient: Mention GUI | 2018-01-03T09:42:26 | [bca1feee4cd8](https://github.com/tldr-pages/tldr/commit/bca1feee4cd89935b1e44a1a873ada08762ba089)
[Jaseem Abid](mailto:jaseemabid@gmail.com) | emacsclient: Improve wording about nowait | 2017-12-29T07:51:32 | [d92c0ab9e41b](https://github.com/tldr-pages/tldr/commit/d92c0ab9e41ba439e39e3f3cae9aaa666bcc874b)
[Jaseem Abid](mailto:jaseemabid@gmail.com) | Add a short tldr page for emacs client | 2017-12-28T11:00:04 | [d61ee9a5e907](https://github.com/tldr-pages/tldr/commit/d61ee9a5e9072d6bbd188797d6159ed2f6fa8860)

