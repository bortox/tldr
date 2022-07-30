---
author: ['James Hibbard']
date: 1592880889
title: "gpgv"
description: "gpgv, Verify OpenPGP signatures."
categories: "common"
---
> More information: <https://www.gnupg.org/documentation/manuals/gnupg/gpgv.html>.

- Verify a signed file:

```bash
gpgv path/to/file
```

- Verify a signed file using a detached signature:

```bash
gpgv path/to/signature path/to/file
```

- Add a file to the list of keyrings (a single exported key also counts as a keyring):

```bash
gpgv --keyring ./alice.keyring path/to/signature path/to/file
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[James Hibbard](mailto:1940994+jameshibbard@users.noreply.github.com) | gpgv: fix typo (#4122) | 2020-06-23T04:54:49 | [16573e0cf003](https://github.com/tldr-pages/tldr/commit/16573e0cf003813476d7b6a7e3f5a3c6f317dc1c)
[James Hibbard](mailto:1940994+jameshibbard@users.noreply.github.com) | gpgv: add page (#4116) | 2020-06-20T05:50:04 | [4972c4bf4dad](https://github.com/tldr-pages/tldr/commit/4972c4bf4dad36c43132edbcb4cab4bfcd554c57)

