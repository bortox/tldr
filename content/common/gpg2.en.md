---
author: ['Julien Jerphanion', 'Matthew Peveler']
date: 1609801173
title: "gpg2"
description: "gpg2, GNU Privacy Guard 2."
categories: "common"
---
> See `gpg` for GNU Privacy Guard 1.

> More information: <https://docs.releng.linuxfoundation.org/en/latest/gpg.html>.

- List imported keys:

```bash
gpg2 --list-keys
```

- Encrypt a specified file for a specified recipient, writing the output to a new file with `.gpg` appended:

```bash
gpg2 --encrypt --recipient alice@example.com path/to/doc.txt
```

- Encrypt a specified file with only a passphrase, writing the output to a new file with `.gpg` appended:

```bash
gpg2 --symmetric path/to/doc.txt
```

- Decrypt a specified file, writing the result to the standard output:

```bash
gpg2 --decrypt path/to/doc.txt.gpg
```

- Import a public key:

```bash
gpg2 --import path/to/public_key.gpg
```

- Export the public key of a specified email address to the standard output:

```bash
gpg2 --export --armor alice@example.com
```

- Export the private key with a specified email address to the standard output:

```bash
gpg2 --export-secret-keys --armor alice@example.com
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Matthew Peveler](mailto:matt.peveler@gmail.com) | gpg2: fix page title to match file name (#5090) Signed-off-by: Matthew Peveler <matt.peveler@gmail.com> | 2021-01-04T23:59:33 | [c25e4e378e4b](https://github.com/tldr-pages/tldr/commit/c25e4e378e4b0088ee541714e008e79d6e36a735)
[Julien Jerphanion](mailto:git@jjerphan.xyz) | gpg2: Add page (#3074) | 2019-06-03T23:02:45 | [ab5a731d2c8f](https://github.com/tldr-pages/tldr/commit/ab5a731d2c8f2f56cc6017b418969b8d78c21fed)

