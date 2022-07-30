---
author: ['Miroslav Shubernetskiy']
date: 1623422214
title: "openvpn3"
description: "openvpn3, OpenVPN 3 Linux client."
categories: "linux"
---
> More information: <https://community.openvpn.net/openvpn/wiki/OpenVPN3Linux>.

- Start a new VPN session:

```bash
openvpn3 session-start --config path/to/config.conf
```

- List established sessions:

```bash
openvpn3 sessions-list
```

- Disconnect the currently established session started with given configuration:

```bash
openvpn3 session-manage --config path/to/config.conf --disconnect
```

- Import VPN configuration:

```bash
openvpn3 config-import --config path/to/config.conf
```

- List imported configurations:

```bash
openvpn3 configs-list
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Miroslav Shubernetskiy](mailto:miroslav@miki725.com) | openvpn3: add page (#6107) | 2021-06-11T16:36:54 | [5b64655ebcbf](https://github.com/tldr-pages/tldr/commit/5b64655ebcbfa7b376aed8e6dc48eac80b101c27)

