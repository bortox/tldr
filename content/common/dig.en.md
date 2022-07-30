---
author: ['Jonathan Reyes', 'George D. Plymale II', 'Maxim Muzafarov', 'Agniva De Sarker', 'Stanley Ulili', 'Bob Strecansky', 'Lucas Gabriel Schneider', 'rprieto', 'bl-ue', 'Seth Falco', 'Ruben Vereecken']
date: 1656325392
title: "dig"
description: "dig, DNS lookup utility."
categories: "common"
---
> More information: <https://manned.org/dig>.

- Lookup the IP(s) associated with a hostname (A records):

```bash
dig +short example.com
```

- Get a detailed answer for a given domain (A records):

```bash
dig +noall +answer example.com
```

- Query a specific DNS record type associated with a given domain name:

```bash
dig +short example.com A|MX|TXT|CNAME|NS
```

- Get all types of records for a given domain name:

```bash
dig example.com ANY
```

- Specify an alternate DNS server to query:

```bash
dig @8.8.8.8 example.com
```

- Perform a reverse DNS lookup on an IP address (PTR record):

```bash
dig -x 8.8.8.8
```

- Find authoritative name servers for the zone and display SOA records:

```bash
dig +nssearch example.com
```

- Perform iterative queries and display the entire trace path to resolve a domain name:

```bash
dig +trace example.com
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Seth Falco](mailto:seth@falco.fun) | *: convert en-GB to en-US (#8155) | 2022-06-27T12:23:12 | [34fde6d16fbc](https://github.com/tldr-pages/tldr/commit/34fde6d16fbc0a3c45fff5903f0fc2597547b1bb)
[Jonathan Reyes](mailto:jreyes33@users.noreply.github.com) | dig: fix more information link (#7724) | 2022-01-27T20:30:27 | [cbd3214b25ef](https://github.com/tldr-pages/tldr/commit/cbd3214b25ef91e2590438cc9669c02f28720ce8)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | dig: simplify more information link | 2021-03-13T22:00:12 | [d2f741b15556](https://github.com/tldr-pages/tldr/commit/d2f741b15556e713a971d6cb48b6666d985a2be5)
[Stanley Ulili](mailto:25522835+stanulilic@users.noreply.github.com) | dig: add more examples (#5416) | 2021-03-11T23:55:01 | [59fef1dcf0db](https://github.com/tldr-pages/tldr/commit/59fef1dcf0dbb3c461bb517a4923617e3773c27e)
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | multiple pages: standardize domain examples (#3010) This change standardizes URL examples in tldr-pages to use the canonical [...] | 2019-05-13T15:33:05 | [ce642b6c12dd](https://github.com/tldr-pages/tldr/commit/ce642b6c12dd502fbe0360732d637357a1c420bf)
[Maxim Muzafarov](mailto:m.muzafarov@gmail.com) | dig: remove google's mention (#2447) | 2018-10-16T00:55:25 | [01b1cf5c812e](https://github.com/tldr-pages/tldr/commit/01b1cf5c812eb5d329e3d68979c17617ca34dcb8)
[Agniva De Sarker](mailto:agnivade@yahoo.co.in) | dig: add more options (#1947) | 2018-02-02T07:43:22 | [d30142fabe9e](https://github.com/tldr-pages/tldr/commit/d30142fabe9ee70d651c106c4d2dd6c03075ad8d)
[Bob Strecansky](mailto:bob.strecansky@gmail.com) | Fixing dependencies | 2017-01-12T05:01:14 | [7a2208f2ec63](https://github.com/tldr-pages/tldr/commit/7a2208f2ec63ed191d74b84241f1a6cf6be27025)
[George D. Plymale II](mailto:georgedp@orbitalimpact.com) | dig.md: add reverse DNS lookup example (#1003) Doing a reverse DNS lookup by typing out the IP address in reverse, plus adding .in- [...] | 2016-08-13T06:01:26 | [dff8f92cf061](https://github.com/tldr-pages/tldr/commit/dff8f92cf06124e2747b48d4f426269072e6fbba)
[Ruben Vereecken](mailto:rubenvereecken@gmail.com) | Formatted all pages according to guidelines. | 2016-01-08T09:38:59 | [066582e8eab5](https://github.com/tldr-pages/tldr/commit/066582e8eab57bce9861cc8d379e158d61f1cc95)
[rprieto](mailto:choicesmade@gmail.com) | Move pages back into a "pages" folder | 2014-03-04T13:28:29 | [f00bf64426a7](https://github.com/tldr-pages/tldr/commit/f00bf64426a792ee3aac792f9c0aec3f8b1eaa7d)

