---
author: ['IacobusKopiirefuto', 'Luca Dorigo']
date: 1607112699
title: "openssl genrsa, TLDR Pages"
description: "openssl genrsa, OpenSSL command to generate RSA private keys."
categories: "common"
---
> More information: <https://www.openssl.org/docs/manmaster/man1/openssl-genrsa.html>.

- Generate an RSA private key of 2048 bits to stdout:

```bash
openssl genrsa
```

- Save an RSA private key of an arbitrary number of bits to the output file:

```bash
openssl genrsa -out output_file.key 1234
```

- Generate an RSA private key and encrypt it with AES256 (you will be prompted for a passphrase):

```bash
openssl genrsa -aes256
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[IacobusKopiirefuto](mailto:71605946+IacobusKopiirefuto@users.noreply.github.com) | openssl-prime: add page (#4422) | 2020-12-04T21:11:39 | [c7ed28053aad](https://github.com/tldr-pages/tldr/commit/c7ed28053aad3cae4fe8dd4b1856a3dc50dc39b1)
[Luca Dorigo](mailto:dorigoluca@gmail.com) | openssl-genrsa: add page (#4050) Co-authored-by: Zlatan Vasović <zlatanvasovic@gmail.com> Co-authored-by: Ein Verne [...] | 2020-05-28T11:03:35 | [9bfeb25d16db](https://github.com/tldr-pages/tldr/commit/9bfeb25d16db94023ffa548b7ff8839cfcfc00f6)

