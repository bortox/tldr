---
author: ['Lucas Gabriel Schneider', 'Guido Lena Cota', 'Starbeamrainbowlabs', 'Marco Bonelli']
date: 1629110041
title: "mkisofs"
description: "mkisofs, Create ISO files from directories."
categories: "linux"
---
> Also aliased as `genisoimage`.

> More information: <https://manned.org/mkisofs>.

- Create an ISO from a directory:

```bash
mkisofs -o filename.iso path/to/source_directory
```

- Set the disc label when creating an ISO:

```bash
mkisofs -o filename.iso -V "label_name" path/to/source_directory
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | linux/[l-m]: add more information link (#6231) | 2021-08-16T12:34:01 | [41db1d238028](https://github.com/tldr-pages/tldr/commit/41db1d2380286234a89aaa2131d8e1d1c531b850)
[Guido Lena Cota](mailto:guido.lenacota@kreuzwerker.de) | Bulk change: move double quotes outside tokens (#4431) | 2020-10-04T19:33:38 | [354d4b8748ee](https://github.com/tldr-pages/tldr/commit/354d4b8748ee58813dd6830ced7c3b11067255d7)
[Marco Bonelli](mailto:mb5.marcob@gmail.com) | Refactor: change "folder" to "directory" where needed. This commit fixes every instance in which the word "folder" is incorrectly used [...] | 2019-02-13T16:21:04 | [2599a6de483a](https://github.com/tldr-pages/tldr/commit/2599a6de483a70601ab17b29e0f18a5a8bdcaa12)
[Starbeamrainbowlabs](mailto:sbrl@starbeamrainbowlabs.com) | Update mkisofs.md | 2017-09-09T18:01:20 | [d4fb4c9046d0](https://github.com/tldr-pages/tldr/commit/d4fb4c9046d0a9ca9f6ae6772368d12882188499)
[Starbeamrainbowlabs](mailto:sbrl@starbeamrainbowlabs.com) | mkisofs: add page | 2017-09-07T16:19:12 | [ccf727ffa430](https://github.com/tldr-pages/tldr/commit/ccf727ffa43019593b2c92733a699a63e9ecc181)
[Starbeamrainbowlabs](mailto:sbrl@starbeamrainbowlabs.com) | Oops! That should be a pull request. | 2017-09-07T16:18:28 | [bff585025b38](https://github.com/tldr-pages/tldr/commit/bff585025b38d1b8a107d8f1d4e9d675369a35bf)
[Starbeamrainbowlabs](mailto:sbrl@starbeamrainbowlabs.com) | mkisofs: add page | 2017-09-07T16:16:40 | [1db12908f0fe](https://github.com/tldr-pages/tldr/commit/1db12908f0fe48f815378826e240f99f807ca858)

