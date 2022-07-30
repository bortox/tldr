---
author: ['Ruslan Kiyanchuk', 'Lucas Gabriel Schneider', 'marchersimon']
date: 1618869951
title: "drill"
description: "drill, Perform various DNS queries."
categories: "common"
---
> More information: <https://manned.org/drill>.

- Lookup the IP(s) associated with a hostname (A records):

```bash
drill example.com
```

- Lookup the mail server(s) associated with a given domain name (MX record):

```bash
drill mx example.com
```

- Get all types of records for a given domain name:

```bash
drill any example.com
```

- Specify an alternate DNS server to query:

```bash
drill example.com @8.8.8.8
```

- Perform a reverse DNS lookup on an IP address (PTR record):

```bash
drill -x 8.8.8.8
```

- Perform DNSSEC trace from root servers down to a domain name:

```bash
drill -TD example.com
```

- Show DNSKEY record(s) for a domain name:

```bash
drill -s dnskey example.com
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[marchersimon](mailto:marchersimon@zohomail.eu) | add more information links | 2021-04-20T00:05:51 | [bc5d06ed1e1e](https://github.com/tldr-pages/tldr/commit/bc5d06ed1e1e112cfb368a38ae5918ef124cdc22)
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | multiple pages: standardize domain examples (#3010) This change standardizes URL examples in tldr-pages to use the canonical [...] | 2019-05-13T15:33:05 | [ce642b6c12dd](https://github.com/tldr-pages/tldr/commit/ce642b6c12dd502fbe0360732d637357a1c420bf)
[Ruslan Kiyanchuk](mailto:ruslan.kiyanchuk@gmail.com) | drill: add page (#2600) | 2018-11-20T05:05:07 | [125fe7192497](https://github.com/tldr-pages/tldr/commit/125fe7192497782651403830562728e42edfe6b8)

