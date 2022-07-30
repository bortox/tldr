---
author: ['Waldir Pimenta', 'Dario Vladović', 'andyxning', 'Igor Shubovych', 'Agniva De Sarker', 'Srinivasan R', 'Ruben Vereecken', 'Robbie S', 'Patrice Denis', 'marchersimon']
date: 1617292466
title: "cat"
description: "cat, Print and concatenate files."
categories: "common"
---
> More information: <https://www.gnu.org/software/coreutils/cat>.

- Print the contents of a file to the standard output:

```bash
cat file
```

- Concatenate several files into the target file:

```bash
cat file1 file2 > target_file
```

- Append several files into the target file:

```bash
cat file1 file2 >> target_file
```

- Number all output lines:

```bash
cat -n file
```

- Display non-printable and whitespace characters (with `M-` prefix if non-ASCII):

```bash
cat -v -t -e file
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Dario Vladović](mailto:d.vladimyr@gmail.com) | coreutils*: use short more info links (#5658) | 2021-04-01T17:54:26 | [4830093903f6](https://github.com/tldr-pages/tldr/commit/4830093903f66ccf3ebbc2ecf477286e45edac59)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | cat: change more information link (#5551) | 2021-03-30T12:31:55 | [3d97ba7785c1](https://github.com/tldr-pages/tldr/commit/3d97ba7785c175e55c9c9ac06f1f20b08837ea5d)
[Patrice Denis](mailto:patrice.denis@gmail.com) | cat: add more info link and update French translation (#5497) | 2021-03-24T22:57:14 | [ea469862762d](https://github.com/tldr-pages/tldr/commit/ea469862762d2762a6a81a0cf85210b057195c6c)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | cat: add -v example (#3163) | 2019-07-03T04:52:13 | [e2c33742e2ec](https://github.com/tldr-pages/tldr/commit/e2c33742e2ec8b0eb4275cc2e0e334c6fcb7f37c)
[Agniva De Sarker](mailto:agnivade@yahoo.co.in) | Applying the snake_case convention throughout the repo (#967) * Applying the snake_case convention throughout the repo - Also removing [...] | 2016-07-22T22:24:06 | [3da76e4150b8](https://github.com/tldr-pages/tldr/commit/3da76e4150b8631fd74aabfcc953cc23731b6bb8)
[andyxning](mailto:andy.xning@gmail.com) | update cat command | 2016-01-18T15:44:34 | [c861a6dc4875](https://github.com/tldr-pages/tldr/commit/c861a6dc4875b9252357db35971bc96a08e5dee1)
[Ruben Vereecken](mailto:rubenvereecken@gmail.com) | Formatted all pages according to guidelines. | 2016-01-08T09:38:59 | [066582e8eab5](https://github.com/tldr-pages/tldr/commit/066582e8eab57bce9861cc8d379e158d61f1cc95)
[Robbie S](mailto:robbie@selwynsoftware.com) | cat: added the append example | 2015-12-30T19:09:53 | [2de7c9f932b0](https://github.com/tldr-pages/tldr/commit/2de7c9f932b0c69abeaa0e6ae12eace2124f2edf)
[Igor Shubovych](mailto:igor.shubovych@gmail.com) | cat: minor fix | 2015-11-23T23:05:54 | [1cb680cdc809](https://github.com/tldr-pages/tldr/commit/1cb680cdc809af03e0dac74c0d44e8238cede889)
[Igor Shubovych](mailto:igor.shubovych@gmail.com) | cat: fix tokens | 2015-11-22T22:09:29 | [b5175c1c58f6](https://github.com/tldr-pages/tldr/commit/b5175c1c58f6819bef7fae34fc07ca9d36ed6da0)
[Srinivasan R](mailto:srinivasanr@gmail.com) | Normalize the final new line Fixes #310 Some files had no newlines, some had 1 newline and some more than 1 newline. Normalize them [...] | 2015-10-28T09:33:06 | [e4114fa6cce7](https://github.com/tldr-pages/tldr/commit/e4114fa6cce7339425809afef817b06e872d7ca7)
[Igor Shubovych](mailto:igor.shubovych@gmail.com) | cat: adding {{token}} syntax | 2014-05-12T13:30:53 | [9639c3d86995](https://github.com/tldr-pages/tldr/commit/9639c3d86995e408883412aafbde06d7ab5e3a20)
[Igor Shubovych](mailto:igor.shubovych@gmail.com) | Pages: cat | 2014-05-10T14:23:41 | [4db7b759098d](https://github.com/tldr-pages/tldr/commit/4db7b759098dd481ebc47832604912b35b832b1f)

