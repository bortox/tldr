---
author: ['Anton Karmanov']
date: 1601691537
title: "openvpn"
description: "openvpn, OpenVPN client and daemon binary."
categories: "common"
---
> More information: <https://openvpn.net/>.

- Connect to server using a config file:

```bash
sudo openvpn path/to/client.conf
```

- Try to set up an insecure peer-to-peer tunnel on bob.example.com host:

```bash
sudo openvpn --remote alice.example.com --dev tun1 --ifconfig 10.4.0.1 10.4.0.2
```

- Connect to the awaiting bob.example.com host without encryption:

```bash
sudo openvpn --remote bob.example.com --dev tun1 --ifconfig 10.4.0.2 10.4.0.1
```

- Create a cryptographic key and save it to file:

```bash
openvpn --genkey --secret path/to/key
```

- Try to set up a peer-to-peer tunnel on bob.example.com host with a static key:

```bash
sudo openvpn --remote alice.example.com --dev tun1 --ifconfig 10.4.0.1 10.4.0.2 --secret path/to/key
```

- Connect to the awaiting bob.example.com host with the same static key as on bob.example.com:

```bash
sudo openvpn --remote bob.example.com --dev tun1 --ifconfig 10.4.0.2 10.4.0.1 --secret path/to/key
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Anton Karmanov](mailto:a.karmanov@inventati.org) | openvpn: add page (#4378) | 2020-10-03T04:18:57 | [77f1cb8009a7](https://github.com/tldr-pages/tldr/commit/77f1cb8009a7887b500bf998572b6af12d5d6f23)

