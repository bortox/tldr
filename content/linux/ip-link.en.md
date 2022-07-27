---
author: ['Adam Herst']
date: 1618153681
title: "ip link, TLDR Pages"
description: "ip link, Manage network interfaces."
categories: "linux"
---
> More information: <https://man7.org/linux/man-pages/man8/ip-link.8.html>.

- Show information about all network interfaces:

```bash
ip link
```

- Show information about a specific network interface:

```bash
ip link show ethN
```

- Bring a network interface up or down:

```bash
ip link set ethN up|down
```

- Give a meaningful name to a network interface:

```bash
ip link set ethN alias "LAN Interface"
```

- Change the MAC address of a network interface:

```bash
ip link set ethN address ff:ff:ff:ff:ff:ff
```

- Change the MTU size for a network interface to use jumbo frames:

```bash
ip link set ethN mtu 9000
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Adam Herst](mailto:adamherst@adamherst.com) | ip-link: edit example Improve wording Co-authored-by: Starbeamrainbowlabs <sbrl@starbeamrainbowlabs.com> | 2021-04-11T17:08:01 | [5bbcb4b4f473](https://github.com/tldr-pages/tldr/commit/5bbcb4b4f473958cdd8233015d012964066782ea)
[Adam Herst](mailto:adamherst@adamherst.com) | ip-link: edit example Move quotation marks outside of the braces. Co-authored-by: Axel Navarro <navarroaxel@gmail.com> | 2021-04-11T17:08:01 | [120a3c3d4fb9](https://github.com/tldr-pages/tldr/commit/120a3c3d4fb956690718836aead06abecf5c5d3d)
[Adam Herst](mailto:adamherst@adamherst.com) | ip-link: edit More information link To point to man7.org. | 2021-04-11T17:08:01 | [93ecc777b852](https://github.com/tldr-pages/tldr/commit/93ecc777b852f1c824adb1dafbb4c1bb32225433)
[Adam Herst](mailto:adamherst@adamherst.com) | Add page. | 2021-04-11T17:08:01 | [d1deb1a86ebd](https://github.com/tldr-pages/tldr/commit/d1deb1a86ebda0469a5d10a5db2cc8cdb35de24e)

