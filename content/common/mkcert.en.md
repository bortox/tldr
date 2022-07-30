---
author: ['Waldir Pimenta', 'Ivan Aracki', 'Guido Lena Cota', 'Marco Bonelli']
date: 1601832818
title: "mkcert"
description: "mkcert, Tool for making locally-trusted development certificates."
categories: "common"
---
> More information: <https://github.com/FiloSottile/mkcert>.

- Install the local CA in the system trust store:

```bash
mkcert -install
```

- Generate certificate and private key for a given domain:

```bash
mkcert example.org
```

- Generate certificate and private key for multiple domains:

```bash
mkcert example.org myapp.dev 127.0.0.1
```

- Generate wildcard certificate and private key for a given domain and its subdomains:

```bash
mkcert "*.example.it"
```

- Uninstall the local CA:

```bash
mkcert -uninstall
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Guido Lena Cota](mailto:guido.lenacota@kreuzwerker.de) | Bulk change: move double quotes outside tokens (#4431) | 2020-10-04T19:33:38 | [354d4b8748ee](https://github.com/tldr-pages/tldr/commit/354d4b8748ee58813dd6830ced7c3b11067255d7)
[Marco Bonelli](mailto:marco@mebeim.net) | Refactor: reword English pages' links' descriptions. | 2019-06-03T14:19:41 | [66abb98ce935](https://github.com/tldr-pages/tldr/commit/66abb98ce935c0f4516bf30c4d6da72180d5a3ab)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | mkcert: minor grammar fix | 2019-04-22T06:00:37 | [084c10c6def9](https://github.com/tldr-pages/tldr/commit/084c10c6def906d5648c2a90845352e66f746082)
[Ivan Aracki](mailto:aracki.ivan@gmail.com) | mkcert: add page (#2934) | 2019-04-20T23:07:23 | [65b79daa35d2](https://github.com/tldr-pages/tldr/commit/65b79daa35d2f0a505ecd37f8c21659278bd0546)

