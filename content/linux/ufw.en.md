---
author: ['nicolae-stroncea', 'Agniva De Sarker', 'CleanMachine1', 'kalebo', 'Torild', 'Guido Lena Cota', 'Danilo Bargen']
date: 1647261933
title: "ufw, TLDR Pages"
description: "ufw, Uncomplicated Firewall."
categories: "linux"
---
> Frontend for iptables aiming to make configuration of a firewall easier.

> More information: <https://wiki.ubuntu.com/UncomplicatedFirewall>.

- Enable ufw:

```bash
ufw enable
```

- Disable ufw:

```bash
ufw disable
```

- Show ufw rules, along with their numbers:

```bash
ufw status numbered
```

- Allow incoming traffic on port 5432 on this host with a comment identifying the service:

```bash
ufw allow 5432 comment "Service"
```

- Allow only TCP traffic from 192.168.0.4 to any address on this host, on port 22:

```bash
ufw allow proto tcp from 192.168.0.4 to any port 22
```

- Deny traffic on port 80 on this host:

```bash
ufw deny 80
```

- Deny all UDP traffic to ports in range 8412:8500:

```bash
ufw deny proto udp from any to any port 8412:8500
```

- Delete a particular rule. The rule number can be retrieved from the `ufw status numbered` command:

```bash
ufw delete rule_number
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[nicolae-stroncea](mailto:39338488+nicolae-stroncea@users.noreply.github.com) | ufw: use range in deny port example (#7881) | 2022-03-14T13:45:33 | [dba098e9251e](https://github.com/tldr-pages/tldr/commit/dba098e9251edaf5e22a7d846e920e1403ec0846)
[CleanMachine1](mailto:78213164+CleanMachine1@users.noreply.github.com) | ufw: add more information link (#6170) | 2021-06-25T06:43:37 | [307895cb3016](https://github.com/tldr-pages/tldr/commit/307895cb3016681c5b3a44570c1f503ffdc9d53f)
[Guido Lena Cota](mailto:guido.lenacota@kreuzwerker.de) | Bulk change: move double quotes outside tokens (#4431) | 2020-10-04T19:33:38 | [354d4b8748ee](https://github.com/tldr-pages/tldr/commit/354d4b8748ee58813dd6830ced7c3b11067255d7)
[kalebo](mailto:kaleb.olson@gmail.com) | Reworded and fixed comment | 2017-10-06T16:37:07 | [2cb67bba3e6f](https://github.com/tldr-pages/tldr/commit/2cb67bba3e6f2df0bfbab804002f3833439dbe8f)
[kalebo](mailto:kaleb.olson@gmail.com) | Added an example of the comment arg | 2017-10-05T23:18:50 | [00ab4dec57a5](https://github.com/tldr-pages/tldr/commit/00ab4dec57a55d302127ea29ee5d9132c4054445)
[Agniva De Sarker](mailto:agnivade@yahoo.co.in) | Changing "Remove" to "Delete" | 2016-09-01T19:21:56 | [f08c58079bb0](https://github.com/tldr-pages/tldr/commit/f08c58079bb0bc2b6ddce43aeb7c45464fa9bc28)
[Agniva De Sarker](mailto:agnivade@yahoo.co.in) | Reordering the syntax to match with the description | 2016-09-01T19:21:56 | [964f07132be8](https://github.com/tldr-pages/tldr/commit/964f07132be8b3bf445dcb527a5f89c00a45acfd)
[Agniva De Sarker](mailto:agnivade@yahoo.co.in) | ufw: Improve page | 2016-09-01T19:21:46 | [7506047a39eb](https://github.com/tldr-pages/tldr/commit/7506047a39eb1e0250373670a7c0cf7fa8bf5dbb)
[Danilo Bargen](mailto:mail@dbrgn.ch) | ufw: Add another example | 2016-05-18T09:21:26 | [72ce264ee73f](https://github.com/tldr-pages/tldr/commit/72ce264ee73f8855972f576ca0889a980261aa32)
[Torild](mailto:torild.lidman@gmail.com) | Create ufw.md Update ufw.md Update ufw.md Update ufw.md Update ufw.md Update ufw.md Update ufw.md | 2016-01-14T21:43:31 | [3233bb7aaba0](https://github.com/tldr-pages/tldr/commit/3233bb7aaba038f90e87a30406b87992247bccd9)

