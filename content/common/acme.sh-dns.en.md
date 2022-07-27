---
author: ['Peter Babič', 'Seth Falco']
date: 1629050349
title: "acme.sh --dns, TLDR Pages"
description: "acme.sh --dns, Use a DNS-01 challenge to issue a TLS certificate."
categories: "common"
---
> More information: <https://github.com/acmesh-official/acme.sh/wiki>.

- Issue a certificate using an automatic DNS API mode:

```bash
acme.sh --issue --dns gnd_gd --domain example.com
```

- Issue a wildcard certificate (denoted by an asterisk) using an automatic DNS API mode:

```bash
acme.sh --issue --dns dns_namesilo --domain example.com --domain *.example.com
```

- Issue a certificate using a DNS alias mode:

```bash
acme.sh --issue --dns dns_cf --domain example.com --challenge-alias alias-for-example-validation.com
```

- Issue a certificate while disabling automatic Cloudflare / Google DNS polling after the DNS record is added by specifying a custom wait time in seconds:

```bash
acme.sh --issue --dns dns_namecheap --domain example.com --dnssleep 300
```

- Issue a certificate using a manual DNS mode:

```bash
acme.sh --issue --dns --domain example.com --yes-I-know-dns-manual-mode-enough-go-ahead-please
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Seth Falco](mailto:seth@falco.fun) | *: fix errors reported by languagetool (#6069) | 2021-08-15T19:59:09 | [3e4c519004a4](https://github.com/tldr-pages/tldr/commit/3e4c519004a471c861cdc609fd7239ee3355671c)
[Peter Babič](mailto:peter@babic.dev) | acme.sh-dns: add page; acme.sh: remove example (#5852) | 2021-05-14T02:49:45 | [345a2d8156bd](https://github.com/tldr-pages/tldr/commit/345a2d8156bd54aec45695b756d8dcffcef91b0e)

