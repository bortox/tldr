---
author: ['ev-john', 'Lucas Gabriel Schneider', 'marchersimon']
date: 1618584134
title: "named"
description: "named, Execute the DNS (Dynamic Name Service) server daemon that converts host names to IP addresses and vice versa."
categories: "linux"
---
> More information: <https://manned.org/named>.

- Read the default configuration file `/etc/named.conf`, read any initial data and listen for queries:

```bash
named
```

- Read a custom configuration file:

```bash
named -c path/to/named.conf
```

- Use IPv4 or IPv6 only, even if the host machine is capable of utilising other protocols:

```bash
named -4|-6
```

- Listen for queries on a specific port instead of the default port 53:

```bash
named -p port
```

- Run the server in the foreground and do not daemonize:

```bash
named -f
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | multiple pages: replace all die.net links (#5528) Most of the links were replaced by manned.org, except when there are more up-to-date [...] | 2021-04-16T16:42:14 | [dac4a710772f](https://github.com/tldr-pages/tldr/commit/dac4a710772f9adef5b9883172fb30ed2416c0eb)
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | multiple pages: format technical tokens (#5119) Co-authored-by: bl-ue <54780737+bl-ue@users.noreply.github.com> Co-authored-by: [...] | 2021-01-31T18:05:18 | [a5fe31bc47ae](https://github.com/tldr-pages/tldr/commit/a5fe31bc47aece3efa5e66b52b3cf384f27d5d72)
[ev-john](mailto:56849582+ev-john@users.noreply.github.com) | named: add page (#4645) | 2020-10-15T00:02:52 | [0684b3a7cb6a](https://github.com/tldr-pages/tldr/commit/0684b3a7cb6af515ed85fd06992d8e76d3b62946)

