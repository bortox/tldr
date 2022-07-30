---
author: ['sebastientinel', 'Starbeamrainbowlabs', 'siavashsoleymani', 'David Hatch', 'marchersimon']
date: 1618756407
title: "badblocks"
description: "badblocks, Search a device for bad blocks."
categories: "common"
---
> Some usages of badblocks can cause destructive actions, such as erasing all data on a disk, including the partition table.

> More information: <https://manned.org/badblocks>.

- Search a disk for bad blocks by using a non-destructive read-only test:

```bash
sudo badblocks /dev/sdX
```

- Search an unmounted disk for bad blocks with a non-destructive read-write test:

```bash
sudo badblocks -n /dev/sdX
```

- Search an unmounted disk for bad blocks with a destructive write test:

```bash
sudo badblocks -w /dev/sdX
```

- Search an unmounted disk for bad blocks with a destructive write test and show verbose status:

```bash
sudo badblocks -svw /dev/sdX
```

- Search an unmounted disk in destructive mode and output found blocks to a file:

```bash
sudo badblocks -o path/to/file -w /dev/sdX
```

- Search an unmounted disk in destructive mode with improved speed using 4K block size and 64K block count:

```bash
sudo badblocks -w -b 4096 -c 65536 /dev/sdX
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[marchersimon](mailto:marchersimon@zohomail.eu) | replace `man.archlinux.org` with `manned.org` | 2021-04-18T16:33:27 | [9abb079afb69](https://github.com/tldr-pages/tldr/commit/9abb079afb6972f3de61a30e1b3fb849ad4b68d9)
[marchersimon](mailto:marchersimon@zohomail.eu) | badblocks: fix link | 2021-04-18T16:33:27 | [9dcaa79cdbd6](https://github.com/tldr-pages/tldr/commit/9dcaa79cdbd60c09b0c06e17d2c7e689a3ab4126)
[marchersimon](mailto:marchersimon@zohomail.eu) | badblocks: add link | 2021-04-18T16:33:27 | [962f1bc5ed08](https://github.com/tldr-pages/tldr/commit/962f1bc5ed08dfe6e4cdb2541bc0fa805e91af71)
[sebastientinel](mailto:sebastien.tinel@gmail.com) | multiple pages: Unify file path syntax to indicate a 'path to' (#4816) | 2020-10-28T18:19:43 | [1d32985f2f24](https://github.com/tldr-pages/tldr/commit/1d32985f2f24e5469dddc993dd7f354f79bfa128)
[siavashsoleymani](mailto:siavash.solimanii@yahoo.com) | badblocks: fix typo | 2020-10-27T12:01:11 | [c6ba2affd5ab](https://github.com/tldr-pages/tldr/commit/c6ba2affd5ab05f866ff0933914c9bc8663708b1)
[David Hatch](mailto:3mail48@gmail.com) | badblocks: add more examples (#3747) Add two examples using verbose mode and output to file. | 2020-01-15T10:50:37 | [1a925460a92c](https://github.com/tldr-pages/tldr/commit/1a925460a92cadefa19cb41eb153f77636d9504f)
[Starbeamrainbowlabs](mailto:sbrl@starbeamrainbowlabs.com) | badblocks: add page (#1399) | 2017-06-11T15:30:40 | [10e9f9d2af3e](https://github.com/tldr-pages/tldr/commit/10e9f9d2af3e5fa1164f6943ea8a4d08bfed0cb1)

