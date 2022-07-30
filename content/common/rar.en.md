---
author: ['Ali Malek', 'Sadeed']
date: 1634106170
title: "rar"
description: "rar, The RAR archiver. Supports multi-volume archives that can be optionally self-extracting."
categories: "common"
---
> More information: <https://manned.org/rar>.

- Archive 1 or more files:

```bash
rar a path/to/archive_name.rar path/to/file1 path/to/file2 path/to/file3
```

- Archive a directory:

```bash
rar a path/to/archive_name.rar path/to/directory
```

- Split the archive into parts of equal size (50M):

```bash
rar a -v50M -R path/to/archive_name.rar path/to/file_or_directory
```

- Password protect the resulting archive:

```bash
rar a -ppassword path/to/archive_name.rar path/to/file_or_directory
```

- Encrypt file data and headers with password:

```bash
rar a -hppassword path/to/archive_name.rar path/to/file_or_directory
```

- Use a specific compression level (0-5):

```bash
rar a -mcompression_level path/to/archive_name.rar path/to/file_or_directory
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Sadeed](mailto:sadeeedw@gmail.com) | rar, read, renice, rev, roll, route, rsync: add link (#6929) | 2021-10-13T08:22:50 | [6583ef2421da](https://github.com/tldr-pages/tldr/commit/6583ef2421da704fdb94b1acb67c70936ccb5ddf)
[Ali Malek](mailto:ali.malek.71@gmail.com) | rar: fix token (#3444) | 2019-10-18T13:08:14 | [346add4ba3f8](https://github.com/tldr-pages/tldr/commit/346add4ba3f889723c64144bc9961c3406ffefe6)
[Ali Malek](mailto:ali.malek.71@gmail.com) | rar: add page (#3414) | 2019-10-17T14:33:11 | [d290603c4422](https://github.com/tldr-pages/tldr/commit/d290603c442233340c0f108ec02155c12edaece9)

