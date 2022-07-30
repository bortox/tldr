---
author: ['Axel Navarro']
date: 1631652137
title: "tailscale up"
description: "tailscale up, Connects the client to the Tailscale network."
categories: "common"
---
> In version 1.8 and above, command line arguments are stored and reused until they're overwritten or `--reset` is called.

> More information: <https://tailscale.com/kb/admin/>.

- Connect to Tailscale:

```bash
sudo tailscale up
```

- Connect and offer the current machine to be an exit node for internet traffic:

```bash
sudo tailscale up --advertise-exit-node
```

- Connect using a specific node for internet traffic:

```bash
sudo tailscale up --exit-node=exit_node_ip
```

- Connect and block incoming connections to the current node:

```bash
sudo tailscale up --shields-up
```

- Connect and don't accept DNS configuration from the admin panel (defaults to `true`):

```bash
sudo tailscale up --accept-dns=false
```

- Connect and configure Tailscale as a subnet router:

```bash
sudo tailscale up --advertise-routes=10.0.0.0/24,10.0.1.0/24
```

- Connect and accept subnet routes from Tailscale:

```bash
sudo tailscale up --accept-routes
```

- Reset unspecified settings to their default values and connect:

```bash
sudo tailscale up --reset
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Axel Navarro](mailto:navarroaxel@gmail.com) | tailscale-up: add page (#6513) | 2021-09-14T22:42:17 | [60e1eda7e214](https://github.com/tldr-pages/tldr/commit/60e1eda7e214bf20ed5238134087f38162131db2)

