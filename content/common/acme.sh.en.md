---
author: ['Peter Babič']
date: 1620953385
title: "acme.sh"
description: "acme.sh, Shell script implementing ACME client protocol, an alternative to certbot."
categories: "common"
---
> See also `acme.sh dns`.

> More information: <https://github.com/acmesh-official/acme.sh>.

- Issue a certificate using webroot mode:

```bash
acme.sh --issue --domain example.com --webroot /path/to/webroot
```

- Issue a certificate for multiple domains using standalone mode using port 80:

```bash
acme.sh --issue --standalone --domain example.com --domain www.example.com
```

- Issue a certificate using standalone TLS mode using port 443:

```bash
acme.sh --issue --alpn --domain example.com
```

- Issue a certificate using a working Nginx configuration:

```bash
acme.sh --issue --nginx --domain example.com
```

- Issue a certificate using a working Apache configuration:

```bash
acme.sh --issue --apache --domain example.com
```

- Issue a wildcard (\*) certificate using an automatic DNS API mode:

```bash
acme.sh --issue --dns dns_cf --domain *.example.com
```

- Install certificate files into the specified locations (useful for automatic certificate renewal):

```bash
acme.sh --install-cert -d example.com --key-file /path/to/example.com.key --fullchain-file /path/to/example.com.cer --reloadcmd "systemctl force-reload nginx"
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Peter Babič](mailto:peter@babic.dev) | acme.sh-dns: add page; acme.sh: remove example (#5852) | 2021-05-14T02:49:45 | [345a2d8156bd](https://github.com/tldr-pages/tldr/commit/345a2d8156bd54aec45695b756d8dcffcef91b0e)
[Peter Babič](mailto:peter@babic.dev) | acme.sh: add page (#5823) * add page: acme.sh * fix 825645081 https://github.com/tldr-pages/tldr/pull/5823#issuecomment-825645081 * [...] | 2021-04-27T18:20:54 | [f1e8d7e06a3c](https://github.com/tldr-pages/tldr/commit/f1e8d7e06a3cabe5d1505f84c8b1f93deb120fe7)

