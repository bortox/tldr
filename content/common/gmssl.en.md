---
author: ['Brad Baker']
date: 1629960053
title: "gmssl, TLDR Pages"
description: "gmssl, GmSSL is a crypto toolkit supporting SM1, SM2, SM3, SM4, SM9, and ZUC/ZUC256."
categories: "common"
---
> More information: <http://gmssl.org/english.html>.

- Generate an SM3 hash for a file:

```bash
gmssl sm3 path/to/file
```

- Encrypt a file using the SM4 cipher:

```bash
gmssl sms4 -e -in path/to/file -out path/to/file.sms4
```

- Decrypt a file using the SM4 cipher:

```bash
gmssl sms4 -d -in path/to/file.sms4
```

- Generate an SM2 private key:

```bash
gmssl sm2 -genkey -out path/to/file.pem
```

- Generate an SM2 public key from an existing private key:

```bash
gmssl sm2 -pubout -in path/to/file.pem -out path/to/file.pem.pub
```

- Encrypt a file using the ZUC cipher:

```bash
gmssl zuc -e -in path/to/file -out path/to/file.zuc
```

- Decrypt a file using the ZUC cipher:

```bash
gmssl zuc -d -in path/to/file.zuc
```

- Print version:

```bash
gmssl version
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Brad Baker](mailto:88946291+brdbkr@users.noreply.github.com) | gmssl: add page (#6408) | 2021-08-26T08:40:53 | [d9921db32014](https://github.com/tldr-pages/tldr/commit/d9921db32014140f8048246c87692baf7f00aefb)

