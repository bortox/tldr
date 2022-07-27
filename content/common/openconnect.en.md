---
author: ['Juri']
date: 1603543675
title: "openconnect, TLDR Pages"
description: "openconnect, A VPN client, for Cisco AnyConnect VPNs and others."
categories: "common"
---
> More information: <https://www.infradead.org/openconnect/manual.html>.

- Connect to a server:

```bash
openconnect vpn.example.org
```

- Connect to a server, forking into the background:

```bash
openconnect --background vpn.example.org
```

- Terminate the connection that is running in the background:

```bash
killall -SIGINT openconnect
```

- Connect to a server, reading options from a config file:

```bash
openconnect --config=path/to/file vpn.example.org
```

- Connect to a server and authenticate with a specific SSL client certificate:

```bash
openconnect --certificate=path/to/file vpn.example.org
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Juri](mailto:juri.dispan@posteo.net) | openconnect: add page (#4780) | 2020-10-24T14:47:55 | [8bee8a1bdbda](https://github.com/tldr-pages/tldr/commit/8bee8a1bdbdaca8244afe3736564c8107dbf1811)

