---
author: ['Waldir Pimenta', 'lord63', 'Ruben Vereecken', 'pxgamer', 'Antoine Gaubert', 'Daniel Senff']
date: 1612462441
title: "fdupes, TLDR Pages"
description: "fdupes, Finds duplicate files in a given set of directories."
categories: "common"
---
> More information: <https://github.com/adrianlopezroche/fdupes>.

- Search a single directory:

```bash
fdupes directory
```

- Search multiple directories:

```bash
fdupes directory1 directory2
```

- Search a directory recursively:

```bash
fdupes -r directory
```

- Search multiple directories, one recursively:

```bash
fdupes directory1 -R directory2
```

- Search recursively for duplicates and display interactive prompt to pick which ones to keep, deleting the others:

```bash
fdupes -rd directory
```

- Search recursively and delete duplicates without prompting:

```bash
fdupes -rdN directory
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Antoine Gaubert](mailto:angauber@student.42lyon.fr) | fdupes: add delete and noprompt examples, add French translation (#5231) | 2021-02-04T19:14:01 | [0f064dff2c48](https://github.com/tldr-pages/tldr/commit/0f064dff2c48a12134a14faeb6b95200f04a64a5)
[pxgamer](mailto:owzie123@gmail.com) | fdupes: add link to homepage | 2019-06-07T23:58:59 | [c96ec5bdce02](https://github.com/tldr-pages/tldr/commit/c96ec5bdce0274f650396f552a0dd8c68d27d169)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | fix descriptions split by mistake in #633 (#1098) | 2016-10-12T17:58:04 | [c15d705d4007](https://github.com/tldr-pages/tldr/commit/c15d705d4007cc9adfa737a0ec6b88bef56656a8)
[Ruben Vereecken](mailto:rubenvereecken@gmail.com) | Formatted all pages according to guidelines. | 2016-01-08T09:38:59 | [066582e8eab5](https://github.com/tldr-pages/tldr/commit/066582e8eab57bce9861cc8d379e158d61f1cc95)
[lord63](mailto:lord63.j@gmail.com) | Fix lint for common | 2015-10-23T02:02:34 | [56a7cba6568f](https://github.com/tldr-pages/tldr/commit/56a7cba6568fcdaaeca2ddf0b80341cfc7de6285)
[Daniel Senff](mailto:mail@danielsenff.de) | Update fdupes.md dang, used the wrong command name, it has to be fdupes instead of fdupe | 2014-09-14T23:29:47 | [87fef5cffa88](https://github.com/tldr-pages/tldr/commit/87fef5cffa8854a89abb411d42e6e161f227dec9)
[Daniel Senff](mailto:mail@danielsenff.de) | add fdupes documentation this is for fdupes: https://github.com/adrianlopezroche/fdupes | 2014-08-23T11:26:21 | [8622386ae37b](https://github.com/tldr-pages/tldr/commit/8622386ae37bc3e55f7522220d325dfba4061bca)

