---
author: ['Mat']
date: 1603911796
title: "openssl x509"
description: "openssl x509, OpenSSL command to manage X.509 certificates."
categories: "common"
---
> More information: <https://www.openssl.org/docs/manmaster/man1/openssl-x509.html>.

- Display certificate information:

```bash
openssl x509 -in filename.crt -noout -text
```

- Display a certificate's expiration date:

```bash
openssl x509 -enddate -noout -in filename.pem
```

- Convert a certificate between binary DER encoding and textual PEM encoding:

```bash
openssl x509 -inform der -outform pem -in original_certificate_file -out converted_certificate_file
```

- Store a certificate's public key in a file:

```bash
openssl x509 -in certificate_file -noout -pubkey -out output_file
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Mat](mailto:mtausig@users.noreply.github.com) | openssl: add subcommand pages (#4886) | 2020-10-28T20:03:16 | [581967789302](https://github.com/tldr-pages/tldr/commit/581967789302fae52733e44aac62f38ed90ab494)

