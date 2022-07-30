---
author: ['Waldir Pimenta', 'Lucas Gabriel Schneider', 'Starbeamrainbowlabs']
date: 1630607629
title: "isoinfo"
description: "isoinfo, Utility programs for dumping and verifying ISO disk images."
categories: "linux"
---
> More information: <https://manned.org/isoinfo>.

- List all the files included in an ISO image:

```bash
isoinfo -f -i path/to/image.iso
```

- E[x]tract a specific file from an ISO image and send it out stdout:

```bash
isoinfo -i path/to/image.iso -x /PATH/TO/FILE/INSIDE/ISO.EXT
```

- Show header information for an ISO disk image:

```bash
isoinfo -d -i path/to/image.iso
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | linux/[h-k]: add more information link (#6227) | 2021-09-02T20:33:49 | [65456d0941d0](https://github.com/tldr-pages/tldr/commit/65456d0941d092a69548cae0ed6e4f4d19bfe9d2)
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | multiple pages: format technical tokens (#5119) Co-authored-by: bl-ue <54780737+bl-ue@users.noreply.github.com> Co-authored-by: [...] | 2021-01-31T18:05:18 | [a5fe31bc47ae](https://github.com/tldr-pages/tldr/commit/a5fe31bc47aece3efa5e66b52b3cf384f27d5d72)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | Harmonize formatting and capitalization of stdin/stdout/stderr | 2019-06-17T18:39:58 | [cf25745db1d8](https://github.com/tldr-pages/tldr/commit/cf25745db1d86744c762e15e6a2ba04ef9f9acc1)
[Starbeamrainbowlabs](mailto:sbrl@starbeamrainbowlabs.com) | isoinfo: add page (#1400) | 2017-06-08T06:23:15 | [efe5302dc127](https://github.com/tldr-pages/tldr/commit/efe5302dc12717fc5a5088b6984f64d4225273ab)

