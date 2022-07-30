---
author: ['Owen Voke']
date: 1609243325
title: "cipher"
description: "cipher, Encrypt or decrypt files on NTFS drives."
categories: "windows"
---
> More information: <https://docs.microsoft.com/windows-server/administration/windows-commands/cipher>.

- Encrypt a file or directory:

```bash
cipher /e:path/to/file_or_directory
```

- Decrypt a file or directory:

```bash
cipher /d:path/to/file_or_directory
```

- Securely remove a file or directory:

```bash
cipher /w:path/to/file_or_directory
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Owen Voke](mailto:development@voke.dev) | cipher: add more information link | 2020-12-29T13:02:05 | [d6612d511cb8](https://github.com/tldr-pages/tldr/commit/d6612d511cb8a8cdddf6022968ed47c0bd29b005)
[Owen Voke](mailto:owzie123@gmail.com) | cipher: add page (#3285) | 2019-10-04T22:36:01 | [32aac2faef52](https://github.com/tldr-pages/tldr/commit/32aac2faef5246117ea2ad79b24e10d2b36a4d9e)

