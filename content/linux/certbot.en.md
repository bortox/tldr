---
author: ['Agniva De Sarker', 'Jonas Alfredsson', 'Starbeamrainbowlabs']
date: 1603125110
title: "certbot, TLDR Pages"
description: "certbot, The Let's Encrypt Agent for automatically obtaining and renewing TLS certificates."
categories: "linux"
---
> Successor to `letsencrypt`.

> More information: <https://certbot.eff.org/docs/using.html>.

- Obtain a new certificate via webroot authorization, but do not install it automatically:

```bash
sudo certbot certonly --webroot --webroot-path path/to/webroot --domain subdomain.example.com
```

- Obtain a new certificate via nginx authorization, installing the new certificate automatically:

```bash
sudo certbot --nginx --domain subdomain.example.com
```

- Obtain a new certificate via apache authorization, installing the new certificate automatically:

```bash
sudo certbot --apache --domain subdomain.example.com
```

- Renew all Let's Encrypt certificates that expire in 30 days or less (don't forget to restart any servers that use them afterwards):

```bash
sudo certbot renew
```

- Simulate the obtaining of a new certificate, but don't actually save any new certificates to disk:

```bash
sudo certbot --webroot --webroot-path path/to/webroot --domain subdomain.example.com --dry-run
```

- Obtain an untrusted test certificate instead:

```bash
sudo certbot --webroot --webroot-path path/to/webroot --domain subdomain.example.com --test-cert
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Jonas Alfredsson](mailto:jonas.alfredsson@protonmail.com) | certbot: add URL to official manual page (#4710) | 2020-10-19T18:31:50 | [c4499982324a](https://github.com/tldr-pages/tldr/commit/c4499982324ac5455d9223a0208f007842f5d565)
[Agniva De Sarker](mailto:agnivade@yahoo.co.in) | certbot: fix minor grammatical mistake (#2156) | 2018-06-26T17:20:04 | [86789ce709bf](https://github.com/tldr-pages/tldr/commit/86789ce709bf10a72901f5f199c6af8ebae95445)
[Starbeamrainbowlabs](mailto:sbrl@starbeamrainbowlabs.com) | certbot: add page (#2030) | 2018-03-19T07:15:16 | [e97bffa53d2f](https://github.com/tldr-pages/tldr/commit/e97bffa53d2f0a245be10abf7566055083f7bbd4)

