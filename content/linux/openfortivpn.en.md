---
author: ['Robby Renz', 'bl-ue']
date: 1607722048
title: "openfortivpn, TLDR Pages"
description: "openfortivpn, A VPN client, for Fortinet's proprietary PPP+SSL VPN solution."
categories: "linux"
---
> More information: <https://github.com/adrienverge/openfortivpn>.

- Connect to a VPN with a username and password:

```bash
openfortivpn --username=username --password=password
```

- Connect to a VPN using a specific configuration file (defaults to `/etc/openfortivpn/config`):

```bash
sudo openfortivpn --config=path/to/config
```

- Connect to a VPN by specifying the host and port:

```bash
openfortivpn host:port
```

- Trust a given gateway by passing in its certificate's sha256 sum:

```bash
openfortivpn --trusted-cert=sha256_sum
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | [many]: fix typos | 2020-12-11T22:27:28 | [2718393db1a3](https://github.com/tldr-pages/tldr/commit/2718393db1a358b04f94effb6a8b16e61647fb0b)
[Robby Renz](mailto:43713843+robbyrenz@users.noreply.github.com) | openfortivpn: add page (#4902) | 2020-11-02T13:06:08 | [c0d84c1dd953](https://github.com/tldr-pages/tldr/commit/c0d84c1dd9530a3b6914e3d5af2b91cfa99695c5)

