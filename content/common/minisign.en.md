---
author: ['FantasyCookie17']
date: 1618755617
title: "minisign, TLDR Pages"
description: "minisign, A dead simple tool to sign files and verify signatures."
categories: "common"
---
> More information: <https://jedisct1.github.io/minisign/>.

- Generate a new keypair at the default location:

```bash
minisign -G
```

- Sign a file:

```bash
minisign -Sm path/to/file
```

- Sign a file, adding a trusted (signed) and an untrusted (unsigned) comment in the signature:

```bash
minisign -Sm path/to/file -c "Untrusted comment" -t "Trusted comment"
```

- Verify a file and the trusted comments in its signature using the specified public key file:

```bash
minisign -Vm path/to/file -p path/to/publickey.pub
```

- Verify a file and the trusted comments in its signature, specifying a public key as a Base64 encoded literal:

```bash
minisign -Vm path/to/file -P "public_key_base64"
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[FantasyCookie17](mailto:fantasycookie17@artemislena.eu) | minisign: add English and German pages (#5757) * Added English and German pages for Minisign * Fixed typo * Fixed the remaining typos [...] | 2021-04-18T16:20:17 | [7cc074d4d5bd](https://github.com/tldr-pages/tldr/commit/7cc074d4d5bd336ed4712727069308839a30c2e3)

