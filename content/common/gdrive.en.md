---
author: ['pxgamer', 'Jonathan F. Kuntz', 'Seth Falco', 'bl-ue']
date: 1629050349
title: "gdrive, TLDR Pages"
description: "gdrive, Command-line tool to interact with Google Drive."
categories: "common"
---
> Folder/file ID can be obtained from the Google Drive folder or ID URL.

> More information: <https://github.com/gdrive-org/gdrive>.

- Upload a local path to the parent folder with the specified ID:

```bash
gdrive upload -p id path/to/file_or_folder
```

- Download file or directory by ID to current directory:

```bash
gdrive download id
```

- Download to a given local path by its ID:

```bash
gdrive download --path path/to/folder id
```

- Create a new revision of an ID using a given file or folder:

```bash
gdrive update id path/to/file_or_folder
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Seth Falco](mailto:seth@falco.fun) | *: fix errors reported by languagetool (#6069) | 2021-08-15T19:59:09 | [3e4c519004a4](https://github.com/tldr-pages/tldr/commit/3e4c519004a471c861cdc609fd7239ee3355671c)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | *: fix typos reported by Hunspell (#5848) Co-authored-by: marchersimon <50295997+marchersimon@users.noreply.github.com> Co-authored- [...] | 2021-05-20T22:13:41 | [8ebd171d6f00](https://github.com/tldr-pages/tldr/commit/8ebd171d6f001698709fefc02b1fd5cc9f3a99c4)
[pxgamer](mailto:owzie123@gmail.com) | gdrive: add link to homepage | 2019-06-07T23:58:59 | [2912ec76fd52](https://github.com/tldr-pages/tldr/commit/2912ec76fd52cebcb3ac0478eb7f10442a2fef80)
[Jonathan F. Kuntz](mailto:jonathanfk1@gmail.com) | gdrive: add page (#2139) | 2018-07-05T06:30:39 | [bffff5ddf911](https://github.com/tldr-pages/tldr/commit/bffff5ddf9117eaf7654e5bebba99c2d6f381563)

