---
author: ['Waldir Pimenta', 'Agniva De Sarker', 'git-em', 'marchersimon']
date: 1646800137
title: "ed"
description: "ed, The original Unix text editor."
categories: "common"
---
> More information: <https://www.gnu.org/software/ed/manual/ed_manual.html>.

- Start ed, editing an empty document (which can be saved as a new file in the current directory):

```bash
ed
```

- Start ed, editing an empty document, with `:` as a command prompt indicator:

```bash
ed -p :
```

- Start ed editing an existing file (this shows the byte count of the loaded file):

```bash
ed -p : path/to/file
```

- Toggle the printing of error explanations. (By default, explanations are not printed and only a `?` appears):

```bash
H
```

- Add text to the current document. Mark completion by entering a period by itself in a new line:

```bash
a<Enter>text_to_insert<Enter>.
```

- Print the entire document (`,` is a shortcut to the range `1,$` which covers the start to the end of the document):

```bash
,p
```

- Write the current document to a new file (the filename can be omitted if `ed` was called with an existing file):

```bash
w filename
```

- Quit ed:

```bash
q
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[git-em](mailto:56173216+git-em@users.noreply.github.com) | common/*: replace man.archlinux.org (#7860) | 2022-03-09T05:28:57 | [a48819f19092](https://github.com/tldr-pages/tldr/commit/a48819f19092a82a1faef1f9f105bc1eb27d2df7)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | ed: add link (#5532) | 2021-03-29T18:34:34 | [609014c1978e](https://github.com/tldr-pages/tldr/commit/609014c1978e51d6b5872b3b47c3000f732a0f21)
[Agniva De Sarker](mailto:agnivade@yahoo.co.in) | Applying the snake_case convention throughout the repo (#967) * Applying the snake_case convention throughout the repo - Also removing [...] | 2016-07-22T22:24:06 | [3da76e4150b8](https://github.com/tldr-pages/tldr/commit/3da76e4150b8631fd74aabfcc953cc23731b6bb8)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | add ed.md (#944) * add ed.md inspired by this very nice introductory blog post: https://sanctum.geek.nz/arabesque/actually-using-ed/ * [...] | 2016-07-10T11:59:29 | [fff4a4c95e57](https://github.com/tldr-pages/tldr/commit/fff4a4c95e57f0e1742984caa66996255149e1cd)

