---
author: ['Mat', 'Julia Evans']
date: 1650025122
title: "openssl s_client, TLDR Pages"
description: "openssl s_client, OpenSSL command to create TLS client connections."
categories: "common"
---
> More information: <https://www.openssl.org/docs/manmaster/man1/openssl-s_client.html>.

- Display the start and expiry dates for a domain's certificate:

```bash
openssl s_client -connect host:port 2>/dev/null | openssl x509 -noout -dates
```

- Display the certificate presented by an SSL/TLS server:

```bash
openssl s_client -connect host:port </dev/null
```

- Set the Server Name Indicator (SNI) when connecting to the SSL/TLS server:

```bash
openssl s_client -connect host:port -servername hostname
```

- Display the complete certificate chain of an HTTPS server:

```bash
openssl s_client -connect host:443 -showcerts </dev/null
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Julia Evans](mailto:julia@jvns.ca) | openssl s_client: add '-servername' (#8002) | 2022-04-15T14:18:42 | [b1c9bce20765](https://github.com/tldr-pages/tldr/commit/b1c9bce20765bd2c3ed0107f0d737eb350bf500f)
[Mat](mailto:mtausig@users.noreply.github.com) | openssl: add subcommand pages (#4886) | 2020-10-28T20:03:16 | [581967789302](https://github.com/tldr-pages/tldr/commit/581967789302fae52733e44aac62f38ed90ab494)

