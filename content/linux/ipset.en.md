---
author: ['Christ0s T4k']
date: 1629969029
title: "ipset"
description: "ipset, A tool to create IP sets for firewall rules."
categories: "linux"
---
> More information: <https://manned.org/ipset>.

- Create an empty IP set which will contain IP addresses:

```bash
ipset create set_name hash:ip
```

- Destroy a specific IP set:

```bash
ipset destroy set_name
```

- Add an IP address to a specific set:

```bash
ipset add set_name 192.168.1.25
```

- Delete a specific IP address from a set:

```bash
ipset del set_name 192.168.1.25
```

- Save an IP set:

```bash
ipset save set_name > path/to/ip_set
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Christ0s T4k](mailto:49581787+christ4k@users.noreply.github.com) | ipset: add page (#6411) | 2021-08-26T11:10:29 | [61b8a6baf14d](https://github.com/tldr-pages/tldr/commit/61b8a6baf14d7e8126279c1a95b9cb40e5b3b833)

