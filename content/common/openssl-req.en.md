---
author: ['Mat', 'bl-ue', 'aherst']
date: 1618083031
title: "openssl req, TLDR Pages"
description: "openssl req, OpenSSL command to manage PKCS#10 Certificate Signing Requests."
categories: "common"
---
> More information: <https://www.openssl.org/docs/manmaster/man1/openssl-req.html>.

- Generate a certificate signing request to be sent to a certificate authority:

```bash
openssl req -new -sha256 -key filename.key -out filename.csr
```

- Generate a self-signed certificate and a corresponding key-pair, storing both in a file:

```bash
openssl req -new -x509 -newkey rsa:4096 -keyout filename.key -out filename.cert -subj "/C=XX/CN=foobar" -days 365
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | autopep8, openssl-req, safe, sn, lvm: fix typo (#5719) | 2021-04-10T21:30:31 | [25a8f14863c7](https://github.com/tldr-pages/tldr/commit/25a8f14863c70faee5373a70c5a1eca82322621e)
[aherst](mailto:adamherst@adamherst.com) | openssl-req: hyphenate self-signed (#5052) | 2020-12-26T22:41:12 | [0e3a93a198a3](https://github.com/tldr-pages/tldr/commit/0e3a93a198a3efb7e015c1522e627fc278046336)
[Mat](mailto:mtausig@users.noreply.github.com) | openssl: add subcommand pages (#4886) | 2020-10-28T20:03:16 | [581967789302](https://github.com/tldr-pages/tldr/commit/581967789302fae52733e44aac62f38ed90ab494)

