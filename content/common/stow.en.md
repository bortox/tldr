---
author: ['Max Strübing', 'Marco Bonelli', 'pxgamer', 'marchersimon']
date: 1620637392
title: "stow"
description: "stow, Symlink manager."
categories: "common"
---
> Often used to manage dotfiles.

> More information: <https://www.gnu.org/software/stow>.

- Symlink all files recursively to a given directory:

```bash
stow --target=path/to/target_directory file1 directory1 file2 directory2
```

- Delete symlinks recursively from a given directory:

```bash
stow --delete --target=path/to/target_directory file1 directory1 file2 directory2
```

- Simulate to see what the result would be like:

```bash
stow --simulate --target=path/to/target_directory file1 directory1 file2 directory2
```

- Delete and resymlink:

```bash
stow --restow --target=path/to/target_directory file1 directory1 file2 directory2
```

- Exclude files matching a regular expression:

```bash
stow --ignore=regular_expression --target=path/to/target_directory file1 directory1 file2 directory2
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | multiple pages: normalize `regular expression` instead of `regex`, `regexp` or `pattern` (#5830) | 2021-05-10T11:03:12 | [10728f1ab485](https://github.com/tldr-pages/tldr/commit/10728f1ab485957d66af3940a030b0fb77611fc0)
[pxgamer](mailto:owzie123@gmail.com) | multiple pages: update the web link descriptions | 2019-05-29T14:41:10 | [f2b1446e6247](https://github.com/tldr-pages/tldr/commit/f2b1446e6247d3e794ee6577dee0c867dfc9af26)
[pxgamer](mailto:owzie123@gmail.com) | stow: add link to homepage | 2019-05-29T14:41:10 | [d4130d15e857](https://github.com/tldr-pages/tldr/commit/d4130d15e857f798344cad45448b50fb7199c362)
[Marco Bonelli](mailto:mb5.marcob@gmail.com) | Refactor: change "folder" to "directory" where needed. This commit fixes every instance in which the word "folder" is incorrectly used [...] | 2019-02-13T16:21:04 | [2599a6de483a](https://github.com/tldr-pages/tldr/commit/2599a6de483a70601ab17b29e0f18a5a8bdcaa12)
[Max Strübing](mailto:mxstrbng@gmail.com) | stow: add page (#1979) | 2018-02-09T19:33:26 | [67b6003970ea](https://github.com/tldr-pages/tldr/commit/67b6003970eaea04a502daf3e71b19646a6bd58a)

