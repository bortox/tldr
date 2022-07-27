---
author: ['Marco Bonelli', 'Scott Sadowsky', 'pxgamer']
date: 1559133670
title: "rclone, TLDR Pages"
description: "rclone, CLI program to copy/sync/move files and directories to and from many cloud services."
categories: "common"
---
> More information: <https://rclone.org>.

- List contents of a directory on an rclone remote:

```bash
rclone lsf remote_name:path/to/directory
```

- Copy file or directory from local source to remote destination:

```bash
rclone copy path/to/source_file_or_directory remote_name:path/to/destination_directory
```

- Copy file or directory from remote source to local destination:

```bash
rclone copy remote_name:path/to/source_file_or_directory path/to/destination_directory
```

- Sync local source to remote destination, changing the destination only:

```bash
rclone sync path/to/file_or_directory remote_name:path/to/directory
```

- Move file or directory from local source to remote destination:

```bash
rclone move path/to/file_or_directory remote_name:path/to/directory
```

- Delete remote file or directory (use `--dry-run` to test, remove it to actually delete):

```bash
rclone --dry-run delete remote_name:path/to/file_or_directory
```

- Mount rclone remote (experimental):

```bash
rclone mount remote_name:path/to/directory path/to/mount_point
```

- Unmount rclone remote if CTRL-C fails (experimental):

```bash
fusermount -u path/to/mount_point
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[pxgamer](mailto:owzie123@gmail.com) | multiple pages: update the web link descriptions | 2019-05-29T14:41:10 | [f2b1446e6247](https://github.com/tldr-pages/tldr/commit/f2b1446e6247d3e794ee6577dee0c867dfc9af26)
[pxgamer](mailto:owzie123@gmail.com) | rclone: add link to homepage | 2019-05-29T14:41:10 | [304ca9eecc93](https://github.com/tldr-pages/tldr/commit/304ca9eecc938b6f22d361635d2570f3a1589598)
[Marco Bonelli](mailto:mb5.marcob@gmail.com) | Refactor: change "folder" to "directory" where needed. This commit fixes every instance in which the word "folder" is incorrectly used [...] | 2019-02-13T16:21:04 | [2599a6de483a](https://github.com/tldr-pages/tldr/commit/2599a6de483a70601ab17b29e0f18a5a8bdcaa12)
[Scott Sadowsky](mailto:Linguista@users.noreply.github.com) | rclone: add page (#2610) | 2019-01-29T04:29:54 | [0cce84d5bcc0](https://github.com/tldr-pages/tldr/commit/0cce84d5bcc0e45b9cfc08f12833392237b264ec)

