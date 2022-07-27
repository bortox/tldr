---
author: ['Waldir Pimenta', 'Ruben Vereecken', 'Camilla Krag Jensen', 'marchersimon', 'Alex Flores']
date: 1632060820
title: "tree, TLDR Pages"
description: "tree, Show the contents of the current directory as a tree."
categories: "common"
---
> More information: <http://mama.indstate.edu/users/ice/tree/>.

- Print files and directories up to 'num' levels of depth (where 1 means the current directory):

```bash
tree -L num
```

- Print directories only:

```bash
tree -d
```

- Print hidden files too with colorization on:

```bash
tree -a -C
```

- Print the tree without indentation lines, showing the full path instead (use `-N` to not escape non-printable characters):

```bash
tree -i -f
```

- Print the size of each file and the cumulative size of each directory, in human-readable format:

```bash
tree -s -h --du
```

- Print files within the tree hierarchy, using a wildcard (glob) pattern, and pruning out directories that don't contain matching files:

```bash
tree -P '*.txt' --prune
```

- Print directories within the tree hierarchy, using the wildcard (glob) pattern, and pruning out directories that aren't ancestors of the wanted one:

```bash
tree -P directory_name --matchdirs --prune
```

- Print the tree ignoring the given directories:

```bash
tree -I 'directory_name1|directory_name2'
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | pwgen, sshuttle, trap, tree: move to common (#6551) | 2021-09-19T16:13:40 | [6474a3284244](https://github.com/tldr-pages/tldr/commit/6474a3284244a623c5ba32264a99d6a27a3bcce3)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | split tree.md into linux and osx versions, to cater to the different sets of available options | 2016-08-24T19:43:14 | [31a07858ca2d](https://github.com/tldr-pages/tldr/commit/31a07858ca2d010625499fb9e942f9c1371b339a)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | tree: use "levels" in the -L example description for improved mnemonics :) | 2016-08-24T18:00:32 | [268af0f8a986](https://github.com/tldr-pages/tldr/commit/268af0f8a986d4108e7f71ca6999b4b54f0af688)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | tree.md: add more useful examples and reorder entries by increasing complexity | 2016-08-24T18:00:31 | [85dcf3eef625](https://github.com/tldr-pages/tldr/commit/85dcf3eef6259acc53ec80e025976267b3a8ae74)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | tree.md: add clarification to -L option (#959) | 2016-07-19T13:39:18 | [5655f1c1f574](https://github.com/tldr-pages/tldr/commit/5655f1c1f57403828bbb0b957ed4d6d84f847c75)
[Ruben Vereecken](mailto:rubenvereecken@gmail.com) | Formatted all pages according to guidelines. | 2016-01-08T09:38:59 | [066582e8eab5](https://github.com/tldr-pages/tldr/commit/066582e8eab57bce9861cc8d379e158d61f1cc95)
[Alex Flores](mailto:eflores@mdsol.com) | adds useful commands to tree | 2015-12-29T17:03:04 | [4a7ece70ace8](https://github.com/tldr-pages/tldr/commit/4a7ece70ace8f986b20cd31fbcc53c1f46e43489)
[Camilla Krag Jensen](mailto:camilla@reload.dk) | Add tree command docs. | 2014-04-14T19:56:07 | [c25dc96b5d23](https://github.com/tldr-pages/tldr/commit/c25dc96b5d23bb24b9258ac2368f0abac1fa8ce1)

