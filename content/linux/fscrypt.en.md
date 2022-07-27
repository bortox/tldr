---
author: ['ezr']
date: 1633461604
title: "fscrypt, TLDR Pages"
description: "fscrypt, Go tool for managing Linux filesystem encryption."
categories: "linux"
---
> More information: <https://github.com/google/fscrypt>.

- Prepare the root filesystem for use with fscrypt:

```bash
fscrypt setup
```

- Enable filesystem encryption for a directory:

```bash
fscrypt encrypt path/to/directory
```

- Unlock an encrypted directory:

```bash
fscrypt unlock path/to/encrypted_directory
```

- Lock an encrypted directory:

```bash
fscrypt lock path/to/encrypted_directory
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[ezr](mailto:ezr@users.noreply.github.com) | fscrypt: add page (#6694) | 2021-10-05T21:20:04 | [247481bf728c](https://github.com/tldr-pages/tldr/commit/247481bf728c75005928365a525d58f4a990479d)

