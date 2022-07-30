---
author: ['bl-ue', 'Stacey Adams']
date: 1621541621
title: "indent"
description: "indent, Change the appearance of a C/C++ program by inserting or deleting whitespace."
categories: "osx"
---
> More information: <https://www.freebsd.org/cgi/man.cgi?query=indent>.

- Format C/C++ source according to the Berkeley style:

```bash
indent path/to/source.c path/to/indented_source.c -nbad -nbap -bc -br -c33 -cd33 -cdb -ce -ci4 -cli0 -di16 -fc1 -fcb -i4 -ip -l75 -lp -npcs -nprs -psl -sc -nsob -ts8
```

- Format C/C++ source according to the style of Kernighan & Ritchie (K&R):

```bash
indent path/to/source.c path/to/indented_source.c -nbad -bap -nbc -br -c33 -cd33 -ncdb -ce -ci4 -cli0 -cs -d0 -di1 -nfc1 -nfcb -i4 -nip -l75 -lp -npcs -nprs -npsl -nsc -nsob
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | *: fix typos reported by Hunspell (#5848) Co-authored-by: marchersimon <50295997+marchersimon@users.noreply.github.com> Co-authored- [...] | 2021-05-20T22:13:41 | [8ebd171d6f00](https://github.com/tldr-pages/tldr/commit/8ebd171d6f001698709fefc02b1fd5cc9f3a99c4)
[Stacey Adams](mailto:stacey.belle.rose@gmail.com) | indent: add page (#4443) | 2020-10-05T16:21:23 | [e50c77099507](https://github.com/tldr-pages/tldr/commit/e50c770995079eeee14f588871f3dc5f83dce8fd)

