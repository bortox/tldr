---
author: ['Miles Glapa-Grossklag', 'Felix Yan', 'dotnetCarpenter', 'Andrea', 'marchersimon']
date: 1648477301
title: "sha512sum"
description: "sha512sum, Calculate SHA512 cryptographic checksums."
categories: "common"
---
> More information: <https://www.gnu.org/software/coreutils/manual/html_node/sha2-utilities.html>.

- Calculate the SHA512 checksum for a file:

```bash
sha512sum path/to/file
```

- Calculate SHA512 checksums for multiple files:

```bash
sha512sum path/to/file1 path/to/file2
```

- Calculate and save the list of SHA512 checksums to a file:

```bash
sha512sum path/to/file1 path/to/file2 > path/to/file.sha512
```

- Read a file of SHA512 sums and verify all files have matching checksums:

```bash
sha512sum --check path/to/file.sha512
```

- Only show a message for missing files or when verification fails:

```bash
sha512sum --check --quiet path/to/file.sha512
```

- Only show a message for files for which verification fails, ignoring missing files:

```bash
sha512sum --ignore-missing --check --quiet path/to/file.sha512
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[dotnetCarpenter](mailto:jon.ronnenberg@gmail.com) | b2sum, md5sum, sha*sum: add --ignore-missing example (#7929) | 2022-03-28T16:21:41 | [b69896935463](https://github.com/tldr-pages/tldr/commit/b69896935463e05ac23cda2d8fca6582b99cdf4a)
[Miles Glapa-Grossklag](mailto:miles@glapa-grossklag.com) | sha512sum: fix file names | 2021-09-05T03:19:57 | [222b5a134479](https://github.com/tldr-pages/tldr/commit/222b5a13447946fa80478440460d51c11b39f440)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | sha*sum: add more information link (#5669) | 2021-04-02T21:05:11 | [44b87621fb9f](https://github.com/tldr-pages/tldr/commit/44b87621fb9fea6dd4e2a3ea5efc3f50e899b4ab)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | sha512sum: add more information link (#5538) | 2021-03-29T22:23:37 | [555daa7bf66f](https://github.com/tldr-pages/tldr/commit/555daa7bf66f335635917031c2368c3f2b80a415)
[Andrea](mailto:agnophi@gmail.com) | sha1sum, sha224sum, sha364sum, sha512sum: Fix wrong command name | 2020-12-30T14:12:18 | [db2961245b2e](https://github.com/tldr-pages/tldr/commit/db2961245b2e41859b784c254c16f7658c46ea0d)
[Andrea](mailto:agnophi@gmail.com) | sha*sum: update description for quiet option Co-authored-by: Starbeamrainbowlabs <sbrl@starbeamrainbowlabs.com> | 2020-12-30T14:12:18 | [87c4f47037af](https://github.com/tldr-pages/tldr/commit/87c4f47037af6faf1bf7c05d3c5b005a088d9e1d)
[Andrea](mailto:agnophi@gmail.com) | sha*sum: fix missing colons | 2020-12-30T14:12:18 | [ffd5838c4e4b](https://github.com/tldr-pages/tldr/commit/ffd5838c4e4bca97d824fa53027fda48fccb8830)
[Andrea](mailto:agnophi@gmail.com) | sha*sum: add example about the creation of a list of checksums | 2020-12-30T14:12:18 | [7076fe8a9cd4](https://github.com/tldr-pages/tldr/commit/7076fe8a9cd4c07d841e317b8c7b588d71404f89)
[Andrea](mailto:agnophi@gmail.com) | sha*sum: change example to long arguments | 2020-12-30T14:12:18 | [45d36431de9c](https://github.com/tldr-pages/tldr/commit/45d36431de9c7ab3b06d835c386cc47018f0e02f)
[Andrea](mailto:agnophi@gmail.com) | sha*: add --quiet option example | 2020-12-30T14:12:18 | [3bde35a542cb](https://github.com/tldr-pages/tldr/commit/3bde35a542cb05ef169ff2b0a3f26ad3d5003723)
[Felix Yan](mailto:felixonmars@archlinux.org) | coreutils commands: move pages to common/ folder (#2442) | 2018-10-16T19:29:50 | [72b4f22ff97b](https://github.com/tldr-pages/tldr/commit/72b4f22ff97b1890344f2af870ad3d1c89a3f0b5)

