---
author: ['Axel Navarro']
date: 1636365839
title: "protonvpn-cli connect"
description: "protonvpn-cli connect, Official client to connect to ProtonVPN from the command-line."
categories: "linux"
---
> More information: <https://protonvpn.com/support/linux-vpn-setup/>.

- Connect to ProtonVPN interactively:

```bash
protonvpn-cli connect
```

- Connect to ProtonVPN using the fastest server available:

```bash
protonvpn-cli connect --fastest
```

- Connect to ProtonVPN using a specific server with a specific protocol:

```bash
protonvpn-cli connect server_name --protocol udp|tcp
```

- Connect to ProtonVPN using a random server with a specific protocol:

```bash
protonvpn-cli connect --random --protocol udp|tcp
```

- Connect to ProtonVPN using the fastest Tor-supporting server:

```bash
protonvpn-cli connect --tor
```

- Display help:

```bash
protonvpn-cli connect --help
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Axel Navarro](mailto:navarroaxel@gmail.com) | protonvpn-cli-connect: fix typo in example (#7395) | 2021-11-08T11:03:59 | [d57f3463ceed](https://github.com/tldr-pages/tldr/commit/d57f3463ceed4c50418d3fe2fcfcebb17110629a)
[Axel Navarro](mailto:navarroaxel@gmail.com) | protonvpn-cli: add page (#6255) | 2021-07-24T21:18:22 | [fa262adaa289](https://github.com/tldr-pages/tldr/commit/fa262adaa289f72bf9c9968a61da7c30e071530c)

