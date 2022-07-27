---
author: ['Jesse Riggins']
date: 1647465655
title: "dog, TLDR Pages"
description: "dog, DNS lookup utility."
categories: "common"
---
> It has colorful output, supports DNS-over-TLS and DNS-over-HTTPS protocols, and can emit JSON.

> More information: <https://dns.lookup.dog>.

- Lookup the IP(s) associated with a hostname (A records):

```bash
dog example.com
```

- Query the MX records type associated with a given domain name:

```bash
dog example.com MX
```

- Specify a specific DNS server to query (e.g. Cloudflare):

```bash
dog example.com MX @1.1.1.1
```

- Query over TCP rather than UDP:

```bash
dog example.com MX @1.1.1.1 --tcp
```

- Query the MX records type associated with a given domain name over TCP using explicit arguments:

```bash
dog --query example.com --type MX --nameserver 1.1.1.1 --tcp
```

- Lookup the IP(s) associated with a hostname (A records) using DNS over HTTPS (DoH):

```bash
dog example.com --https @https://cloudflare-dns.com/dns-query
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Jesse Riggins](mailto:jriggins@users.noreply.github.com) | dog: add page (#7892) | 2022-03-16T22:20:55 | [d2d57c7d3815](https://github.com/tldr-pages/tldr/commit/d2d57c7d38156c166d459a51fc32ee000f4322ef)

