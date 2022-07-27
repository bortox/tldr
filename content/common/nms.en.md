---
author: ['Gonzalo Contreras Aso', 'bl-ue']
date: 1621541621
title: "nms, TLDR Pages"
description: "nms, Command-line tool that recreates the famous data decryption effect seen in the 1992 movie Sneakers from stdin."
categories: "common"
---
> More information: <https://github.com/bartobri/no-more-secrets>.

- Decrypt text after a keystroke:

```bash
echo "Hello, World!" | nms
```

- Decrypt output immediately, without waiting for a keystroke:

```bash
ls -la | nms -a
```

- Decrypt the content of a file, with a custom output color:

```bash
cat path/to/file | nms -a -f blue|white|yellow|black|magenta|green|red
```

- Clear the screen before decrypting:

```bash
command | nms -a -c
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | *: fix typos reported by Hunspell (#5848) Co-authored-by: marchersimon <50295997+marchersimon@users.noreply.github.com> Co-authored- [...] | 2021-05-20T22:13:41 | [8ebd171d6f00](https://github.com/tldr-pages/tldr/commit/8ebd171d6f001698709fefc02b1fd5cc9f3a99c4)
[Gonzalo Contreras Aso](mailto:61254163+goznalo-git@users.noreply.github.com) | nms: add page (#5483) | 2021-03-25T22:55:28 | [e7421cee1358](https://github.com/tldr-pages/tldr/commit/e7421cee1358e1c59ead1e1e3b9f0922f4dd736b)

