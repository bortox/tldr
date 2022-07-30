---
author: ['Waldir Pimenta', 'Emily Grace Seville', 'Severen Redwood']
date: 1647882468
title: "xsel"
description: "xsel, X11 selection and clipboard manipulation tool."
categories: "linux"
---
> More information: <https://manned.org/xsel>.

- Use a command's output as input of the clip[b]oard (equivalent to `Ctrl + C`):

```bash
echo 123 | xsel -ib
```

- Use the contents of a file as input of the clipboard:

```bash
cat file | xsel -ib
```

- Output the clipboard's contents into the terminal (equivalent to `Ctrl + V`):

```bash
xsel -ob
```

- Output the clipboard's contents into a file:

```bash
xsel -ob > file
```

- Clear the clipboard:

```bash
xsel -cb
```

- Output the X11 primary selection's contents into the terminal (equivalent to a mouse middle-click):

```bash
xsel -op
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Emily Grace Seville](mailto:emilyseville7cf@gmail.com) | linux/*: add more information link (#7848) | 2022-03-21T18:07:48 | [4659bcb243ac](https://github.com/tldr-pages/tldr/commit/4659bcb243ac572c9e0c95117097801f1e62bda4)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | change all keyboard shortcuts to have spaces around the + sign (#1356) | 2017-04-29T00:34:51 | [433370e2ad4c](https://github.com/tldr-pages/tldr/commit/433370e2ad4c946240af47231397315eb803695f)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | standardize format of keyboard shortcuts (#1354) * fix capitalization of keyboard shortcuts (elinks, tmux, screen) * adjust formatting [...] | 2017-04-28T09:44:50 | [7e1f06ade4d8](https://github.com/tldr-pages/tldr/commit/7e1f06ade4d869f8c1690fd04c25d8476c46b198)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | fix format | 2016-06-25T10:43:21 | [e99c5fd155ea](https://github.com/tldr-pages/tldr/commit/e99c5fd155eaa26898f131b90900ee253e4744b1)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | simplify xsel.md, add example using X11 selection Also add equivalence to standard operations, to make it clearer what each example does. | 2016-06-25T03:07:46 | [ed0c87bf203c](https://github.com/tldr-pages/tldr/commit/ed0c87bf203cde7cdc0d589f136ad9a399046a5a)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | fix typo in xsel.md | 2016-06-21T00:39:56 | [2b4ecd4131d9](https://github.com/tldr-pages/tldr/commit/2b4ecd4131d9832bc6a213c367e1b22cc3ba4276)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | minor fixes to xsel, as discussed in #882 | 2016-06-21T00:39:21 | [a47218cfca25](https://github.com/tldr-pages/tldr/commit/a47218cfca2589ffa583d8f485c1a3fbc289c166)
[Severen Redwood](mailto:severen@shrike.me) | xsel: Add page (#882) | 2016-06-21T00:36:03 | [fac92c4aa1a1](https://github.com/tldr-pages/tldr/commit/fac92c4aa1a1a28f912fcf7ff4942ea67369c897)

