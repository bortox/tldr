---
author: ['Axel Navarro']
date: 1631652137
title: "tailscale"
description: "tailscale, A private WireGuard network service."
categories: "common"
---
> Some subcommands such as `tailscale up` have their own usage documentation.

> More information: <https://tailscale.com>.

- Connect to Tailscale:

```bash
sudo tailscale up
```

- Disconnect from Tailscale:

```bash
sudo tailscale down
```

- Display the current Tailscale IP addresses:

```bash
tailscale ip
```

- Ping a peer node at the Tailscale layer and display which route it took for each response:

```bash
tailscale ping ip|hostname
```

- Analyze the local network conditions and display the result:

```bash
tailscale netcheck
```

- Start a web server for controlling Tailscale:

```bash
tailscale web
```

- Display a shareable identifier to help diagnose issues:

```bash
tailscale bugreport
```

- Display help for a subcommand:

```bash
tailscale subcommand --help
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Axel Navarro](mailto:navarroaxel@gmail.com) | tailscale-up: add page (#6513) | 2021-09-14T22:42:17 | [60e1eda7e214](https://github.com/tldr-pages/tldr/commit/60e1eda7e214bf20ed5238134087f38162131db2)
[Axel Navarro](mailto:navarroaxel@gmail.com) | tailscale: add page (#6480) | 2021-09-07T18:35:27 | [705759e61743](https://github.com/tldr-pages/tldr/commit/705759e61743eadd90db0be37203f297d02de5c7)

