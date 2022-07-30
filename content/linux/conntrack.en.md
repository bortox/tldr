---
author: ['Adrien Thebo']
date: 1652511982
title: "conntrack"
description: "conntrack, Interact with the Netfilter connection tracking system."
categories: "linux"
---
> Search, list, inspect, modify, and delete connection flows.

> More information: <https://manned.org/conntrack>.

- List all currently tracked connections:

```bash
conntrack --dump
```

- Display a real-time event log of connection changes:

```bash
conntrack --event
```

- Display a real-time event log of connection changes and associated timestamps:

```bash
conntrack --event -o timestamp
```

- Display a real-time event log of connection changes for a specific IP address:

```bash
conntrack --event --orig-src ip_address
```

- Delete all flows for a specific source IP address:

```bash
conntrack --delete --orig-src ip_address
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Adrien Thebo](mailto:adrien@lagrange-automation.io) | conntrack: add page (#8081) * conntrack: add page * Update pages/linux/conntrack.md Co-authored-by: Emily Grace Seville [...] | 2022-05-14T09:06:22 | [bc8eae779fda](https://github.com/tldr-pages/tldr/commit/bc8eae779fda6c78cc1be86fd79dc562a1f0d27b)

