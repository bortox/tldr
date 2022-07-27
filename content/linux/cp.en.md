---
author: ['Danny Kim', 'FantasyCookie17', 'yurai007']
date: 1619634874
title: "cp, TLDR Pages"
description: "cp, Copy files and directories."
categories: "linux"
---
> More information: <https://www.gnu.org/software/coreutils/cp>.

- Copy a file to another location:

```bash
cp path/to/source_file.ext path/to/target_file.ext
```

- Copy a file into another directory, keeping the filename:

```bash
cp path/to/source_file.ext path/to/target_parent_directory
```

- Recursively copy a directory's contents to another location (if the destination exists, the directory is copied inside it):

```bash
cp -r path/to/source_directory path/to/target_directory
```

- Copy a directory recursively, in verbose mode (shows files as they are copied):

```bash
cp -vr path/to/source_directory path/to/target_directory
```

- Copy text files to another location, in interactive mode (prompts user before overwriting):

```bash
cp -i *.txt path/to/target_directory
```

- Follow symbolic links before copying:

```bash
cp -L link path/to/target_directory
```

- Use the full path of source files, creating any missing intermediate directories when copying:

```bash
cp --parents source/path/to/file path/to/target_file
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[FantasyCookie17](mailto:fantasycookie17@artemislena.eu) | cp: add more information link (#5853) | 2021-04-28T20:34:34 | [d03a29e4109e](https://github.com/tldr-pages/tldr/commit/d03a29e4109ee52e0a30835124691d6f8f187346)
[FantasyCookie17](mailto:fantasycookie17@artemislena.eu) | cp: change 'dereference' to 'follow' (#5843) | 2021-04-27T23:02:42 | [3595c42ccefe](https://github.com/tldr-pages/tldr/commit/3595c42ccefe16488cee36507de3ebd62365addf)
[Danny Kim](mailto:DanielKim1@users.noreply.github.com) | cp: replace ambiguous text (#4223) | 2020-07-25T11:19:46 | [ba92cdcc4b2b](https://github.com/tldr-pages/tldr/commit/ba92cdcc4b2b19da23ee7e9c9d581fb8d36bb127)
[yurai007](mailto:dawid_jurek@vp.pl) | cp: add examples for common -L and Linux specific --parents (#4026) (#4026) | 2020-05-13T01:54:45 | [7b3a9b20ace2](https://github.com/tldr-pages/tldr/commit/7b3a9b20ace2f2d19cf610c932bafc056c879fb4)

