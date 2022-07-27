---
author: ['Felix Yan', 'Miles Glapa-Grossklag', 'Andrea', 'dotnetCarpenter', 'marchersimon']
date: 1648477301
title: "sha256sum, TLDR Pages"
description: "sha256sum, Calculate SHA256 cryptographic checksums."
categories: "common"
---
> More information: <https://www.gnu.org/software/coreutils/manual/html_node/sha2-utilities.html>.

- Calculate the SHA256 checksum for a file:

```bash
sha256sum path/to/file
```

- Calculate SHA256 checksums for multiple files:

```bash
sha256sum path/to/file1 path/to/file2
```

- Calculate and save the list of SHA256 checksums to a file:

```bash
sha256sum path/to/file1 path/to/file2 > path/to/file.sha256
```

- Read a file of SHA256 sums and verify all files have matching checksums:

```bash
sha256sum --check path/to/file.sha256
```

- Only show a message for missing files or when verification fails:

```bash
sha256sum --check --quiet path/to/file.sha256
```

- Only show a message for files for which verification fails, ignoring missing files:

```bash
sha256sum --ignore-missing --check --quiet path/to/file.sha256
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[dotnetCarpenter](mailto:jon.ronnenberg@gmail.com) | b2sum, md5sum, sha*sum: add --ignore-missing example (#7929) | 2022-03-28T16:21:41 | [b69896935463](https://github.com/tldr-pages/tldr/commit/b69896935463e05ac23cda2d8fca6582b99cdf4a)
[Miles Glapa-Grossklag](mailto:miles@glapa-grossklag.com) | sha256sum: fix file names | 2021-09-05T03:19:57 | [7cffccc95099](https://github.com/tldr-pages/tldr/commit/7cffccc95099f60de0a90ca971e6519536226dd1)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | sha*sum: add more information link (#5669) | 2021-04-02T21:05:11 | [44b87621fb9f](https://github.com/tldr-pages/tldr/commit/44b87621fb9fea6dd4e2a3ea5efc3f50e899b4ab)
[Andrea](mailto:agnophi@gmail.com) | sha*sum: update description for quiet option Co-authored-by: Starbeamrainbowlabs <sbrl@starbeamrainbowlabs.com> | 2020-12-30T14:12:18 | [87c4f47037af](https://github.com/tldr-pages/tldr/commit/87c4f47037af6faf1bf7c05d3c5b005a088d9e1d)
[Andrea](mailto:agnophi@gmail.com) | sha*sum: fix missing colons | 2020-12-30T14:12:18 | [ffd5838c4e4b](https://github.com/tldr-pages/tldr/commit/ffd5838c4e4bca97d824fa53027fda48fccb8830)
[Andrea](mailto:agnophi@gmail.com) | sha*sum: add example about the creation of a list of checksums | 2020-12-30T14:12:18 | [7076fe8a9cd4](https://github.com/tldr-pages/tldr/commit/7076fe8a9cd4c07d841e317b8c7b588d71404f89)
[Andrea](mailto:agnophi@gmail.com) | sha*sum: change example to long arguments | 2020-12-30T14:12:18 | [45d36431de9c](https://github.com/tldr-pages/tldr/commit/45d36431de9c7ab3b06d835c386cc47018f0e02f)
[Andrea](mailto:agnophi@gmail.com) | sha256: add missing colon | 2020-12-30T14:12:18 | [1b4c23259b01](https://github.com/tldr-pages/tldr/commit/1b4c23259b01e03c0282d3bb976aa502b8b42c1c)
[Andrea](mailto:agnophi@gmail.com) | sha256sum: add --quiet option example | 2020-12-30T14:12:18 | [0bfca8e30d03](https://github.com/tldr-pages/tldr/commit/0bfca8e30d0361b3558570eb32b2646d396bb677)
[Felix Yan](mailto:felixonmars@archlinux.org) | coreutils commands: move pages to common/ folder (#2442) | 2018-10-16T19:29:50 | [72b4f22ff97b](https://github.com/tldr-pages/tldr/commit/72b4f22ff97b1890344f2af870ad3d1c89a3f0b5)

