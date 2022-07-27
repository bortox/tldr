---
author: ['Waldir Pimenta', 'Wolfgang Lutz', 'Maxime Loliée', 'Muhammad Falak R Wani', 'pxgamer', 'amir', 'bl-ue']
date: 1623417741
title: "fzf, TLDR Pages"
description: "fzf, Command-line fuzzy finder."
categories: "common"
---
> Similar to `sk`.

> More information: <https://github.com/junegunn/fzf>.

- Start fzf on all files in the specified directory:

```bash
find path/to/directory -type f | fzf
```

- Start fzf for running processes:

```bash
ps aux | fzf
```

- Select multiple files with `Shift + Tab` and write to a file:

```bash
find path/to/directory -type f | fzf --multi > filename
```

- Start fzf with a specified query:

```bash
fzf --query "query"
```

- Start fzf on entries that start with core and end with either go, rb, or py:

```bash
fzf --query "^core go$ | rb$ | py$"
```

- Start fzf on entries that not match pyc and match exactly travis:

```bash
fzf --query "!pyc 'travis"
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Muhammad Falak R Wani](mailto:falakreyaz@gmail.com) | fzf: refresh wording of examples (#6112) Co-authored-by: Muhammad Falak Wani <mwani@microsoft.com> | 2021-06-11T15:22:21 | [2aa806202d2a](https://github.com/tldr-pages/tldr/commit/2aa806202d2a451068f9ad419f39bd7cb7087d25)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | *: fix typos reported by Hunspell (#5848) Co-authored-by: marchersimon <50295997+marchersimon@users.noreply.github.com> Co-authored- [...] | 2021-05-20T22:13:41 | [8ebd171d6f00](https://github.com/tldr-pages/tldr/commit/8ebd171d6f001698709fefc02b1fd5cc9f3a99c4)
[pxgamer](mailto:owzie123@gmail.com) | fzf: add link to homepage | 2019-06-07T23:58:59 | [7ec153f5c4dd](https://github.com/tldr-pages/tldr/commit/7ec153f5c4ddbb800e5363c65d68510d9e392034)
[amir](mailto:amiralisobhgol@gmail.com) | fix typo (#1809) | 2017-12-18T11:33:49 | [c89117f412d4](https://github.com/tldr-pages/tldr/commit/c89117f412d42dd69d388705b49a821b6a3a1635)
[Wolfgang Lutz](mailto:WLBORg@gmx.de) | fix typos using misspell (#1374) | 2017-05-12T11:29:18 | [550ede5cfb90](https://github.com/tldr-pages/tldr/commit/550ede5cfb90cb772d1ecf27241b22e5086b024b)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | change all keyboard shortcuts to have spaces around the + sign (#1356) | 2017-04-29T00:34:51 | [433370e2ad4c](https://github.com/tldr-pages/tldr/commit/433370e2ad4c946240af47231397315eb803695f)
[Maxime Loliée](mailto:maxime@siliadev.com) | fzf: add page | 2016-02-04T20:56:56 | [ee92bc748880](https://github.com/tldr-pages/tldr/commit/ee92bc748880cbebd36cc2de800ed137bc57209b)

