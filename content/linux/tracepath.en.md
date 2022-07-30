---
author: ['Peter Babič']
date: 1618598889
title: "tracepath"
description: "tracepath, Trace the path to a network host discovering MTU along this path."
categories: "linux"
---
> More information: <https://manned.org/tracepath>.

- A preferred way to trace the path to a host:

```bash
tracepath -p 33434 host
```

- Specify the initial destination port, useful with non-standard firewall settings:

```bash
tracepath -p destination_port host 
```

- Print both hostnames and numerical IP addresses:

```bash
tracepath -b host
```

- Specify a maximum TTL (number of hops):

```bash
tracepath -m max_hops host
```

- Specify the initial packet length (defaults to 65535 for IPv4 and 128000 for IPv6):

```bash
tracepath -l packet_length host
```

- Use only IPv6 addresses:

```bash
tracepath -6 host
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Peter Babič](mailto:peter@babic.dev) | tracepath: add page (#5744) * tracepath: add page * Apply suggestions from code review Co-authored-by: marchersimon [...] | 2021-04-16T20:48:09 | [4d0dc77896ac](https://github.com/tldr-pages/tldr/commit/4d0dc77896ac630e4388a3e874d30864cac36a95)

