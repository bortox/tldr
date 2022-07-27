---
author: ['pxgamer', 'Marco Bonelli', 'Seth Falco']
date: 1629050349
title: "arping, TLDR Pages"
description: "arping, Discover and probe hosts in a network using the ARP protocol."
categories: "common"
---
> Useful for MAC address discovery.

> More information: <https://github.com/ThomasHabets/arping>.

- Ping a host by ARP request packets:

```bash
arping host_ip
```

- Ping a host on a specific interface:

```bash
arping -I interface host_ip
```

- Ping a host and stop at the first reply:

```bash
arping -f host_ip
```

- Ping a host a specific number of times:

```bash
arping -c count host_ip
```

- Broadcast ARP request packets to update neighbours' ARP caches:

```bash
arping -U ip_to_broadcast
```

- Detect duplicated IP addresses in the network by sending ARP requests with a 3 second timeout:

```bash
arping -D -w 3 ip_to_check
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Seth Falco](mailto:seth@falco.fun) | *: fix errors reported by languagetool (#6069) | 2021-08-15T19:59:09 | [3e4c519004a4](https://github.com/tldr-pages/tldr/commit/3e4c519004a471c861cdc609fd7239ee3355671c)
[pxgamer](mailto:owzie123@gmail.com) | arping: add link to homepage | 2019-06-09T18:53:49 | [7d0a9ecbe501](https://github.com/tldr-pages/tldr/commit/7d0a9ecbe5012c8254900928c17028a2618f9417)
[Marco Bonelli](mailto:mb5.marcob@gmail.com) | arping: fix wording and syntax | 2019-04-09T18:39:48 | [fb5181f7a372](https://github.com/tldr-pages/tldr/commit/fb5181f7a37266eb0331e44eba5f1943bead0ec5)
[Marco Bonelli](mailto:mb5.marcob@gmail.com) | arping: add page | 2019-04-09T18:39:48 | [39d735eed751](https://github.com/tldr-pages/tldr/commit/39d735eed7511cb7ce8cd9e85895940084a79ab8)

