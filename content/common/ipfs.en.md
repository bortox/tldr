---
author: ['Austin', 'Francesco Yoshi Gobbo', 'Schneider', 'Marco Bonelli', 'pxgamer', 'Lucas Gabriel Schneider']
date: 1601735886
title: "ipfs, TLDR Pages"
description: "ipfs, Inter Planetary File System."
categories: "common"
---
> A peer-to-peer hypermedia protocol. Aims to make the web more open.

> More information: <https://ipfs.io>.

- Add a file from local to the filesystem, pin it and print the relative hash:

```bash
ipfs add filename
```

- Add a directory and its files recursively from local to the filesystem and print the relative hash:

```bash
ipfs add -r directory
```

- Save a remote file and give it a name but not pin it:

```bash
ipfs get hash -o filename
```

- Pin a remote file locally:

```bash
ipfs pin add hash
```

- Display pinned files:

```bash
ipfs pin ls
```

- Unpin a file from the local storage:

```bash
ipfs pin rm hash
```

- Remove unpinned files from local storage:

```bash
ipfs repo gc
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Austin](mailto:Hoi15A@users.noreply.github.com) | cryfs, df, dfc, fls, ipfs, duperemove, edquote, lsattr, diskutil: (#4427) consistently use "filesystem" | 2020-10-03T16:38:06 | [cfe462c57f20](https://github.com/tldr-pages/tldr/commit/cfe462c57f20c344dad34717378c442dc32cadc2)
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | ipfs.md: update description Co-Authored-By: Starbeamrainbowlabs <sbrl@starbeamrainbowlabs.com> | 2019-10-13T05:28:04 | [9559a85db49f](https://github.com/tldr-pages/tldr/commit/9559a85db49f3cc2732127513bac8f84d631a1ce)
[Schneider](mailto:lucas.schneider@sap.com) | multiple pages: rephrase without adjectives | 2019-10-13T05:28:04 | [42152ed45923](https://github.com/tldr-pages/tldr/commit/42152ed459230c2b244529f0c5990335e0057c6c)
[pxgamer](mailto:owzie123@gmail.com) | ipfs: add link to homepage | 2019-06-06T04:42:48 | [defe8def16ab](https://github.com/tldr-pages/tldr/commit/defe8def16abd904801507e7d3c5cca313b6f5b0)
[Marco Bonelli](mailto:mb5.marcob@gmail.com) | Refactor: change "folder" to "directory" where needed. This commit fixes every instance in which the word "folder" is incorrectly used [...] | 2019-02-13T16:21:04 | [2599a6de483a](https://github.com/tldr-pages/tldr/commit/2599a6de483a70601ab17b29e0f18a5a8bdcaa12)
[Francesco Yoshi Gobbo](mailto:yoshi@fgobbo.com) | ipfs: add page (#2100) | 2018-05-09T09:28:33 | [8f0cf8c65343](https://github.com/tldr-pages/tldr/commit/8f0cf8c65343fa8020650d6bffca4848bcee64fc)

