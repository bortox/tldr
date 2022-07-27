---
author: ['Mat']
date: 1603896856
title: "openssl dgst, TLDR Pages"
description: "openssl dgst, OpenSSL command to generate digest values and perform signature operations."
categories: "common"
---
> More information: <https://www.openssl.org/docs/manmaster/man1/openssl-dgst.html>.

- Calculate the SHA256 digest for a file, saving the result to a specific file:

```bash
openssl dgst -sha256 -binary -out output_file input_file
```

- Sign a file using an RSA key, saving the result to a specific file:

```bash
openssl dgst -sign private_key_file -sha256 -sigopt rsa_padding_mode:pss -out output_file input_file
```

- Verify an RSA signature:

```bash
openssl dgst -verify public_key_file -signature signature_file -sigopt rsa_padding_mode:pss signature_message_file
```

- Sign a file using and ECDSA key:

```bash
openssl dgst -sign private_key_file -sha256 -out output_file input_file
```

- Verify an ECDSA signature:

```bash
openssl dgst -verify public_key_file -signature signature_file signature_message_file
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Mat](mailto:mtausig@users.noreply.github.com) | openssl-dgst, openssl-genpkey: add page (#4879) | 2020-10-28T15:54:16 | [8b07793aa628](https://github.com/tldr-pages/tldr/commit/8b07793aa62837aeced69901a378d91e82869d46)

