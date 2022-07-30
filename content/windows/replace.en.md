---
author: ['Calum Dingwall', 'bl-ue']
date: 1610307737
title: "replace"
description: "replace, Replace files."
categories: "windows"
---
> See also: `robocopy`, `move`, `copy`, and `del`.

> More information: <https://docs.microsoft.com/windows-server/administration/windows-commands/replace>.

- Replace the destination file with the one from the source directory:

```bash
replace path/to/file_or_directory path/to/destination
```

- Add files to the destination directory instead of replacing existing files:

```bash
replace path/to/file_or_directory path/to/destination /a
```

- Interactively copy multiple files, with a prompt before replacing or adding a destination file:

```bash
replace path/to/file_or_directory path/to/destination /p
```

- Replace even read only files:

```bash
replace path/to/file_or_directory path/to/destination /r
```

- Wait for you to insert a disk before it replaces files (originally to allow inserting a floppy disk):

```bash
replace path/to/file_or_directory path/to/destination /w
```

- Replace all files in subdirectories of the destination:

```bash
replace path/to/file_or_directory path/to/destination /s
```

- Replace only files in the destination directory which are older than the files in the source directory:

```bash
replace path/to/file_or_directory path/to/destination /u
```

- Display detailed usage information:

```bash
replace /?
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | replace: change folder to directory | 2021-01-10T20:42:17 | [2497b9b24f20](https://github.com/tldr-pages/tldr/commit/2497b9b24f20dd94a25ae9f0be8077cb72a6aed1)
[Calum Dingwall](mailto:24cdingwall@gmail.com) | replace: add page (#4482) | 2020-10-06T17:49:43 | [ffa4c6b7f810](https://github.com/tldr-pages/tldr/commit/ffa4c6b7f8100e2af4875cc05c6417bc2df7f6a6)

