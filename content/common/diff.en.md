---
author: ['Waldir Pimenta', 'Alexander', 'rprieto', 'lord63', 'marchersimon', 'Mehrad Mahmoudian', 'Ruben Vereecken']
date: 1632132581
title: "diff"
description: "diff, Compare files and directories."
categories: "common"
---
> More information: <https://man7.org/linux/man-pages/man1/diff.1.html>.

- Compare files (lists changes to turn `old_file` into `new_file`):

```bash
diff old_file new_file
```

- Compare files, ignoring white spaces:

```bash
diff --ignore-all-space old_file new_file
```

- Compare files, showing the differences side by side:

```bash
diff --side-by-side old_file new_file
```

- Compare files, showing the differences in unified format (as used by `git diff`):

```bash
diff --unified old_file new_file
```

- Compare directories recursively (shows names for differing files/directories as well as changes made to files):

```bash
diff --recursive old_directory new_directory
```

- Compare directories, only showing the names of files that differ:

```bash
diff --recursive --brief old_directory new_directory
```

- Create a patch file for Git from the differences of two text files, treating nonexistent files as empty:

```bash
diff --text --unified --new-file old_file new_file > diff.patch
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Mehrad Mahmoudian](mailto:m.mahmoudian@gmail.com) | diff: add -Naur create patch file example (#6484) | 2021-09-20T12:09:41 | [96100f42d337](https://github.com/tldr-pages/tldr/commit/96100f42d33787963b97aeee82024800724a09c0)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | 7za, 7zr, aapt, ab, alacritty, atom, avrdude, chown, chroot, clear, cmake, compare, curl, dd, diff: add German translation (#5286) | 2021-02-20T21:30:55 | [e3c79db0e6d4](https://github.com/tldr-pages/tldr/commit/e3c79db0e6d482c9312bcb4a8131085a9dbf9af4)
[Alexander](mailto:2683344+terminalnode@users.noreply.github.com) | diff: clarified and elaborated examples (#3000) | 2019-05-09T18:16:35 | [4fbd0a50ca32](https://github.com/tldr-pages/tldr/commit/4fbd0a50ca3299fe18f6bbf382ea4bbba29ba4ec)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | diff: add -u (unified diff) example (#2462) | 2018-10-19T11:42:28 | [22bdcd575b44](https://github.com/tldr-pages/tldr/commit/22bdcd575b44c805e75a44042efad4c8a2fd8451)
[Ruben Vereecken](mailto:rubenvereecken@gmail.com) | Formatted all pages according to guidelines. | 2016-01-08T09:38:59 | [066582e8eab5](https://github.com/tldr-pages/tldr/commit/066582e8eab57bce9861cc8d379e158d61f1cc95)
[lord63](mailto:lord63.j@gmail.com) | Fix lint for common | 2015-10-23T02:02:34 | [56a7cba6568f](https://github.com/tldr-pages/tldr/commit/56a7cba6568fcdaaeca2ddf0b80341cfc7de6285)
[rprieto](mailto:choicesmade@gmail.com) | Move pages back into a "pages" folder | 2014-03-04T13:28:29 | [f00bf64426a7](https://github.com/tldr-pages/tldr/commit/f00bf64426a792ee3aac792f9c0aec3f8b1eaa7d)

