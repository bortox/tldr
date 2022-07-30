---
author: ['dwdh']
date: 1647074117
title: "kdig"
description: "kdig, Advanced DNS lookup utility."
categories: "common"
---
> More information: <https://www.knot-dns.cz/docs/latest/html/man_kdig.html>.

- Lookup the IP(s) associated with a hostname (A records):

```bash
kdig example.com
```

- Specify a specific DNS server to query (e.g. Google DNS):

```bash
kdig example.com @8.8.8.8
```

- Query a specific DNS record type associated with a given domain name:

```bash
kdig example.com A|AAAA|NS|SOA|DNSKEY|ANY
```

- Lookup the IP(s) associated with a hostname (A records) using DNS over TLS (DoT):

```bash
kdig -d @8.8.8.8 +tls-ca +tls-host=dns.google example.com
```

- Lookup the IP(s) associated with a hostname (A records) using DNS over HTTPS (DoH):

```bash
kdig -d @1.1.1.1 +https +tls-hostname=1dot1dot1dot1.cloudflare-dns.com example.com
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[dwdh](mailto:dylan.donghai.wong@outlook.com) | kdig: add page (#7784) * kdig: add page * Update kdig.md * Update pages/common/kdig.md Co-authored-by: Axel Navarro [...] | 2022-03-12T09:35:17 | [bebfa4e96525](https://github.com/tldr-pages/tldr/commit/bebfa4e965256c2e7fefa0aabf1d775a92c4fb3a)

