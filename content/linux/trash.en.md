---
author: ['jxu', 'CleanMachine1', 'Fealthas', 'Starbeamrainbowlabs', 'marchersimon']
date: 1651684335
title: "trash, TLDR Pages"
description: "trash, A CLI for managing the trashcan / recycling bin."
categories: "linux"
---
> More information: <https://github.com/andreafrancia/trash-cli>.

- Delete a file and send it to the trash:

```bash
trash path/to/file
```

- List all files in the trash:

```bash
trash-list
```

- Interactively restore a file from the trash:

```bash
trash-restore
```

- Empty the trash:

```bash
trash-empty
```

- Permanently delete all files in the trash which are older than 10 days:

```bash
trash-empty 10
```

- Remove all files in the trash, which match a specific blob pattern:

```bash
trash-rm "*.o"
```

- Remove all files with a specific original location:

```bash
trash-rm /path/to/file_or_directory
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[CleanMachine1](mailto:78213164+CleanMachine1@users.noreply.github.com) | *: fix spelling mistakes (#8072) | 2022-05-04T19:12:15 | [c2a5c8603386](https://github.com/tldr-pages/tldr/commit/c2a5c8603386f1720b996b839802fae1fb60ba8a)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | trash: refresh (#7388) | 2021-11-12T20:37:45 | [ec9b5d98c6cb](https://github.com/tldr-pages/tldr/commit/ec9b5d98c6cb2db4c66a4a57b29e389e3383c64b)
[Starbeamrainbowlabs](mailto:sbrl@starbeamrainbowlabs.com) | trash: fix token syntax (#4073) | 2020-05-28T11:57:32 | [e414560b9e13](https://github.com/tldr-pages/tldr/commit/e414560b9e13933c1ee96a33a9d198a0493f5a88)
[jxu](mailto:7989982+jxu@users.noreply.github.com) | trash: add trash-rm examples (#3910) | 2020-03-20T22:03:32 | [19b68e7063e4](https://github.com/tldr-pages/tldr/commit/19b68e7063e4ff101d2e93a01595ddb3126c064d)
[Fealthas](mailto:konplus12@yahoo.com) | trash: add page (#3197) * Create trash.md for trash-cli * Update trash.md add period to pass checkbot * Update trash.md goddam windows [...] | 2019-08-01T15:44:24 | [a6cbd19eee1c](https://github.com/tldr-pages/tldr/commit/a6cbd19eee1ceef8c632411960b4feafb6a0cb19)

