---
author: ['MT', 'bl-ue']
date: 1617494937
title: "tcptraceroute"
description: "tcptraceroute, A traceroute implementation using TCP packets."
categories: "linux"
---
> More information: <https://github.com/mct/tcptraceroute>.

- Trace the route to a host:

```bash
tcptraceroute host
```

- Specify the destination port and packet length in bytes:

```bash
tcptraceroute host destination_port packet_length
```

- Specify the local source port and source address:

```bash
tcptraceroute host -p source_port -s source_address
```

- Set the first and maximum TTL:

```bash
tcptraceroute host -f first_ttl -m max_ttl
```

- Specify the wait time and number of queries per hop:

```bash
tcptraceroute host -w wait_time -q number_of_queries
```

- Specify the interface:

```bash
tcptraceroute host -i interface
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | *: clean up token syntax delimiters (#5677) | 2021-04-04T02:08:57 | [289787c7e8c1](https://github.com/tldr-pages/tldr/commit/289787c7e8c1177742d23004198253154fe50c3c)
[MT](mailto:59728838+mt-empty@users.noreply.github.com) | tcptraceroute: better wording (#3937) | 2020-03-28T22:04:01 | [4f3c09734283](https://github.com/tldr-pages/tldr/commit/4f3c097342835099fc763323e707960f72a7ea64)
[MT](mailto:59728838+mt-empty@users.noreply.github.com) | tcptraceroute: add page (#3849) | 2020-02-20T16:56:59 | [b100ac99cd4e](https://github.com/tldr-pages/tldr/commit/b100ac99cd4e89204eaba2c3eb2003a5c04010ce)

