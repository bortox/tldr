---
author: ['Waldir Pimenta', 'Marco Bonelli', 'Agniva De Sarker', 'pxgamer', 'FlyingJester']
date: 1560099229
title: "cpio, TLDR Pages"
description: "cpio, Copies files in and out of archives."
categories: "common"
---
> Supports the following archive formats: cpio's custom binary, old ASCII, new ASCII, crc, HPUX binary, HPUX old ASCII, old tar, and POSIX.1 tar.

> More information: <https://www.gnu.org/software/cpio>.

- Take a list of file names from standard input and add them [o]nto an archive in cpio's binary format:

```bash
echo "file1 file2 file3" | cpio -o > archive.cpio
```

- Copy all files and directories in a directory and add them [o]nto an archive, in [v]erbose mode:

```bash
find path/to/directory | cpio -ov > archive.cpio
```

- P[i]ck all files from an archive, generating [d]irectories where needed, in [v]erbose mode:

```bash
cpio -idv < archive.cpio
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[pxgamer](mailto:owzie123@gmail.com) | cpio: add link to homepage | 2019-06-09T18:53:49 | [73058253e4e8](https://github.com/tldr-pages/tldr/commit/73058253e4e83e07c2cb23b12609fc801364a322)
[Marco Bonelli](mailto:mb5.marcob@gmail.com) | Refactor: improve consistency of the term "directory". This commit changes the term "folder" to "directory" in every instance where [...] | 2019-02-08T20:43:24 | [ac4094e0ad70](https://github.com/tldr-pages/tldr/commit/ac4094e0ad70a6be2163b06d24b53992b93aee4f)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | cpio: qualify "(custom) binary format" | 2016-09-15T00:30:06 | [df7fd7a1f12f](https://github.com/tldr-pages/tldr/commit/df7fd7a1f12f5375210f81a6ca8a45031611cbe4)
[Agniva De Sarker](mailto:agnivade@yahoo.co.in) | cpio: Re-modify descriptions to match flags - Also fixed a minor grammar error | 2016-09-14T18:48:01 | [143394bda41d](https://github.com/tldr-pages/tldr/commit/143394bda41df2577ca185ab72b990bcb2e3e55b)
[Agniva De Sarker](mailto:agnivade@yahoo.co.in) | cpio: add detailed description about archive format | 2016-09-13T08:35:19 | [1ecdf192380b](https://github.com/tldr-pages/tldr/commit/1ecdf192380b1fdaf429ccae0e25ff72d0ee076a)
[Agniva De Sarker](mailto:agnivade@yahoo.co.in) | cpio: Update description to match flags | 2016-09-10T18:32:57 | [1a8f54c3753d](https://github.com/tldr-pages/tldr/commit/1a8f54c3753df6fda7671ce31228a51724100ade)
[FlyingJester](mailto:foolkingcrown@gmail.com) | cpio: add page | 2016-09-07T19:47:08 | [a53fb05c9554](https://github.com/tldr-pages/tldr/commit/a53fb05c9554f8b1da10da26e836011a271d1ce1)

