---
author: ['Miles Glapa-Grossklag', 'Andrea', 'Zlatan Vasović', 'Sarah Haïm-Lubczanski', 'Lucas Gabriel Schneider']
date: 1635865901
title: "shasum, TLDR Pages"
description: "shasum, Calculate or check cryptographic SHA checksums."
categories: "common"
---
> More information: <https://manned.org/shasum>.

- Calculate the SHA1 checksum for a file:

```bash
shasum path/to/file
```

- Calculate the SHA256 checksum for a file:

```bash
shasum --algorithm 256 path/to/file
```

- Calculate the SHA512 checksum for multiple files:

```bash
shasum --algorithm 512 path/to/file1 path/to/file2
```

- Calculate and save the list of SHA256 checksums to a file:

```bash
shasum --algorithm 256 path/to/file1 path/to/file2 > path/to/file.sha256
```

- Check a file with a list of sums against the directory's files:

```bash
shasum --check path/to/file
```

- Check a list of sums and only show a message for files for which verification fails:

```bash
shasum --check --quiet path/to/file
```

- Calculate the SHA1 checksum from stdin:

```bash
some_command | shasum
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Sarah Haïm-Lubczanski](mailto:205895+mere-teresa@users.noreply.github.com) | shasum: add more information link (#7321) | 2021-11-02T16:11:41 | [547f0a5c1eea](https://github.com/tldr-pages/tldr/commit/547f0a5c1eea57ffb3ccb622c0bb54eb8bb6b55a)
[Miles Glapa-Grossklag](mailto:miles@glapa-grossklag.com) | shasum: fix file names | 2021-09-05T03:19:57 | [df745b0cdc8c](https://github.com/tldr-pages/tldr/commit/df745b0cdc8c0c441d26ac186312139f0683bcdb)
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | multiple pages: format technical tokens (#5119) Co-authored-by: bl-ue <54780737+bl-ue@users.noreply.github.com> Co-authored-by: [...] | 2021-01-31T18:05:18 | [a5fe31bc47ae](https://github.com/tldr-pages/tldr/commit/a5fe31bc47aece3efa5e66b52b3cf384f27d5d72)
[Andrea](mailto:agnophi@gmail.com) | sha*sum: update description for quiet option Co-authored-by: Starbeamrainbowlabs <sbrl@starbeamrainbowlabs.com> | 2020-12-30T14:12:18 | [87c4f47037af](https://github.com/tldr-pages/tldr/commit/87c4f47037af6faf1bf7c05d3c5b005a088d9e1d)
[Andrea](mailto:agnophi@gmail.com) | sha*sum: fix missing colons | 2020-12-30T14:12:18 | [ffd5838c4e4b](https://github.com/tldr-pages/tldr/commit/ffd5838c4e4bca97d824fa53027fda48fccb8830)
[Andrea](mailto:agnophi@gmail.com) | sha*sum: add example about the creation of a list of checksums | 2020-12-30T14:12:18 | [7076fe8a9cd4](https://github.com/tldr-pages/tldr/commit/7076fe8a9cd4c07d841e317b8c7b588d71404f89)
[Andrea](mailto:agnophi@gmail.com) | sha*sum: change example to long arguments | 2020-12-30T14:12:18 | [45d36431de9c](https://github.com/tldr-pages/tldr/commit/45d36431de9c7ab3b06d835c386cc47018f0e02f)
[Andrea](mailto:agnophi@gmail.com) | sha*: add --quiet option example | 2020-12-30T14:12:18 | [3bde35a542cb](https://github.com/tldr-pages/tldr/commit/3bde35a542cb05ef169ff2b0a3f26ad3d5003723)
[Zlatan Vasović](mailto:zlatanvasovic@gmail.com) | shasum: move into common (#3999) | 2020-04-22T03:44:35 | [c234e815945c](https://github.com/tldr-pages/tldr/commit/c234e815945c3897194430c4c1f5373cb0d3cc8e)

