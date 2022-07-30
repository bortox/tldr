---
author: ['Axel Navarro']
date: 1627154302
title: "protonvpn-cli"
description: "protonvpn-cli, Official client for ProtonVPN service from the command-line."
categories: "linux"
---
> More information: <https://github.com/ProtonVPN/linux-cli>.

- Log in to the ProtonVPN account:

```bash
protonvpn-cli login username
```

- Start a kill switch upon connecting to ProtonVPN:

```bash
protonvpn-cli killswitch --on
```

- Connect to ProtonVPN interactively:

```bash
protonvpn-cli connect
```

- Display connection status:

```bash
protonvpn-cli status
```

- Block malware using ProtonVPN NetShield:

```bash
protonvpn-cli netshield --malware
```

- Disconnect from ProtonVPN:

```bash
protonvpn-cli disconnect
```

- Display the current ProtonVPN configuration:

```bash
protonvpn-cli config --list
```

- Display help for a subcommand:

```bash
protonvpn-cli subcommand --help
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Axel Navarro](mailto:navarroaxel@gmail.com) | protonvpn-cli: add page (#6255) | 2021-07-24T21:18:22 | [fa262adaa289](https://github.com/tldr-pages/tldr/commit/fa262adaa289f72bf9c9968a61da7c30e071530c)

