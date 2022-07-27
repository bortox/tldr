---
author: ['258204', 'CleanMachine1']
date: 1657497901
title: "resolvectl, TLDR Pages"
description: "resolvectl, Resolve domain names, IPV4 and IPv6 addresses, DNS resource records, and services."
categories: "linux"
---
> Introspect and reconfigure the DNS resolver.

> More information: <https://www.freedesktop.org/software/systemd/man/resolvectl.html>.

- Show DNS settings:

```bash
resolvectl status
```

- Resolve the IPv4 and IPv6 addresses for one or more domains:

```bash
resolvectl query domain1 domain2 ...
```

- Retrieve the domain of a specified IP:

```bash
resolvectl query ip_address
```

- Retrieve an MX record of domain:

```bash
resolvectl --legend=no --type=MX query domain
```

- Resolve an SRV record, for example _xmpp-server._tcp gmail.com:

```bash
resolvectl service _service._protocol name
```

- Retrieve the public key from an email address from an OPENPGPKEY DNS record:

```bash
resolvectl opengpg email
```

- Retrieve a TLS key:

```bash
resolvectl tlsa tcp domain:443
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[CleanMachine1](mailto:78213164+CleanMachine1@users.noreply.github.com) | linux/*: fix spelling errors | 2022-07-11T02:05:01 | [42bb014b2f6e](https://github.com/tldr-pages/tldr/commit/42bb014b2f6eab426e6225c75a2ec49105813983)
[258204](mailto:71364336+258204@users.noreply.github.com) | resolvectl: add page (#7484) | 2021-12-05T21:30:39 | [6ced4b1e7374](https://github.com/tldr-pages/tldr/commit/6ced4b1e7374d649bddd2309467e2cf7f449508e)

