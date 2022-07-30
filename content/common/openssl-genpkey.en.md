---
author: ['Mat']
date: 1603896856
title: "openssl genpkey"
description: "openssl genpkey, OpenSSL command to generate asymmetric key pairs."
categories: "common"
---
> More information: <https://www.openssl.org/docs/manmaster/man1/openssl-genpkey.html>.

- Generate an RSA private key of 2048 bits, saving it to a specific file:

```bash
openssl genpkey -algorithm rsa -pkeyopt rsa_keygen_bits:2048 -out filename.key
```

- Generate an elliptic curve private key using the curve `prime256v1`, saving it to a specific file:

```bash
openssl genpkey -algorithm EC -pkeyopt ec_paramgen_curve:prime256v1 -out filename.key
```

- Generate an `ED25519` elliptic curve private key, saving it to a specific file:

```bash
openssl genpkey -algorithm ED25519 -out filename.key
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Mat](mailto:mtausig@users.noreply.github.com) | openssl-dgst, openssl-genpkey: add page (#4879) | 2020-10-28T15:54:16 | [8b07793aa628](https://github.com/tldr-pages/tldr/commit/8b07793aa62837aeced69901a378d91e82869d46)

