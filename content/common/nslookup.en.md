---
author: ['Joshua Shanks', 'Yuri Slobodyanyuk']
date: 1633563243
title: "nslookup"
description: "nslookup, Query name server(s) for various domain records."
categories: "common"
---
> More information: <https://manned.org/nslookup>.

- Query your system's default name server for an IP address (A record) of the domain:

```bash
nslookup example.com
```

- Query a given name server for a NS record of the domain:

```bash
nslookup -type=NS example.com 8.8.8.8
```

- Query for a reverse lookup (PTR record) of an IP address:

```bash
nslookup -type=PTR 54.240.162.118
```

- Query for ANY available records using TCP protocol:

```bash
nslookup -vc -type=ANY example.com 
```

- Query a given name server for the whole zone file (zone transfer) of the domain using TCP protocol:

```bash
nslookup -vc -type=AXFR example.com name_server
```

- Query for a mail server (MX record) of the domain, showing details of the transaction:

```bash
nslookup -type=MX -debug example.com
```

- Query a given name server on a specific port number for a TXT record of the domain:

```bash
nslookup -port=port_number -type=TXT example.com name_server
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Joshua Shanks](mailto:jjshanks@gmail.com) | nslookup, objdump, pactl, passwd, patch: add link (#6828) | 2021-10-07T01:34:03 | [d91120d92e31](https://github.com/tldr-pages/tldr/commit/d91120d92e31e12fa2bd5723fb386d9fe05438bf)
[Yuri Slobodyanyuk](mailto:yuri@yurisk.info) | nslookup: add page (#1174) Non interactive use of nslookup on *nix-like systems: https://linux.die.net/man/1/nslookup | 2017-01-24T22:22:44 | [62c4fba2794d](https://github.com/tldr-pages/tldr/commit/62c4fba2794df52a1348a746c3f9a5c3ac5e544c)

