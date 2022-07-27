---
author: ['Marco Bonelli', 'Igor Shubovych', 'Dario Vladović', 'Hayden Schiff', 'marchersimon']
date: 1617292466
title: "chgrp, TLDR Pages"
description: "chgrp, Change group ownership of files and directories."
categories: "common"
---
> More information: <https://www.gnu.org/software/coreutils/chgrp>.

- Change the owner group of a file/directory:

```bash
chgrp group path/to/file_or_directory
```

- Recursively change the owner group of a directory and its contents:

```bash
chgrp -R group path/to/directory
```

- Change the owner group of a symbolic link:

```bash
chgrp -h group path/to/symlink
```

- Change the owner group of a file/directory to match a reference file:

```bash
chgrp --reference=path/to/reference_file path/to/file_or_directory
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Dario Vladović](mailto:d.vladimyr@gmail.com) | coreutils*: use short more info links (#5658) | 2021-04-01T17:54:26 | [4830093903f6](https://github.com/tldr-pages/tldr/commit/4830093903f66ccf3ebbc2ecf477286e45edac59)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | chgrp: add more information link (#5554) | 2021-03-30T12:33:21 | [1bee28dd6572](https://github.com/tldr-pages/tldr/commit/1bee28dd6572c855d7cdb2ffd88e05794a8cfc86)
[Marco Bonelli](mailto:mb5.marcob@gmail.com) | Refactor: change "folder" to "directory" where needed. This commit fixes every instance in which the word "folder" is incorrectly used [...] | 2019-02-13T16:21:04 | [2599a6de483a](https://github.com/tldr-pages/tldr/commit/2599a6de483a70601ab17b29e0f18a5a8bdcaa12)
[Marco Bonelli](mailto:mb5.marcob@gmail.com) | Refactor: add missing `or_directory` where needed. This commit adds the missing `_or_directory` to any example which is specifying an [...] | 2019-02-08T20:43:24 | [f79f6011e0f2](https://github.com/tldr-pages/tldr/commit/f79f6011e0f298311848b5f38d66c309d4b92665)
[Marco Bonelli](mailto:mebeim@users.noreply.github.com) | chgrp: fix typo and clarify examples. (#2738) | 2019-01-30T12:16:17 | [1064ba26dbbf](https://github.com/tldr-pages/tldr/commit/1064ba26dbbf8e1ea20c3af1065212adc061959b)
[Igor Shubovych](mailto:igor.shubovych@gmail.com) | Linting | 2016-02-23T02:54:19 | [ab54477533c8](https://github.com/tldr-pages/tldr/commit/ab54477533c8d173fa4d30cf3146ac7c450d54d6)
[Hayden Schiff](mailto:oxguy3@gmail.com) | chgrp: add page | 2016-02-22T21:03:35 | [e1a8a590e16f](https://github.com/tldr-pages/tldr/commit/e1a8a590e16f4d3aee6fdf4e43e31e976ca772ba)

