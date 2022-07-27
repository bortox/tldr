---
author: ['Guido Lena Cota', 'siavash', 'skitau', 'marchersimon']
date: 1620952935
title: "azcopy, TLDR Pages"
description: "azcopy, A file transfer tool for uploading to Azure Cloud Storage Accounts."
categories: "windows"
---
> More information: <https://docs.microsoft.com/azure/storage/common/storage-use-azcopy-v10>.

- Log in to an Azure Tenant:

```bash
azopy login
```

- Upload a local file:

```bash
azcopy copy 'path/to/source/file' 'https://storage_account_name.blob.core.windows.net/container_name/blob_name'
```

- Upload files with `.txt` and `.jpg` extensions:

```bash
azcopy copy 'path/to/source' 'https://storage_account_name.blob.core.windows.net/container_name' --include-pattern '*.txt;*.jpg'
```

- Copy a container directly between two Azure storage accounts:

```bash
azcopy copy 'https://source_storage_account_name.blob.core.windows.net/container_name' 'https://destination_storage_account_name.blob.core.windows.net/container_name'
```

- Synchronize a local directory and delete files in the destination if they no longer exist in the source:

```bash
azcopy sync 'path/to/source' 'https://storage_account_name.blob.core.windows.net/container_name' --recursive --delete-destination=true
```

- Display detailed usage information:

```bash
azcopy --help
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | change login/logout to `log in`/`log out` (#5920) | 2021-05-14T02:42:15 | [be88cdda9201](https://github.com/tldr-pages/tldr/commit/be88cdda9201a6262af27d8788e222b5df98cc9c)
[Guido Lena Cota](mailto:guido.lenacota@gmail.com) | multiple pages: Use snake_case in token syntax (#4788) | 2020-11-01T14:40:05 | [0bb9c353a717](https://github.com/tldr-pages/tldr/commit/0bb9c353a717513283f8cda8493e5370ca47219a)
[siavash](mailto:siavash.solimanii@yahoo.com) | bedtools, oc, sensible-editor, azcopy: fix typos and add oc project example (#4822) | 2020-10-24T14:58:11 | [71f4635d88d0](https://github.com/tldr-pages/tldr/commit/71f4635d88d0071425a5ee00ad1de49cefa763ac)
[skitau](mailto:robert@blackstock.id.au) | azcopy: add missing token syntax (#4674) | 2020-10-13T12:52:04 | [4f58f4c19eda](https://github.com/tldr-pages/tldr/commit/4f58f4c19edae171499e844d7b555b2c610596ab)
[skitau](mailto:robert@blackstock.id.au) | azcopy: add page (#4569) | 2020-10-12T05:53:17 | [1fcec872b1ee](https://github.com/tldr-pages/tldr/commit/1fcec872b1ee6bc123e003564edb271c4f3fdc74)

