---
author: ['Nguyễn Đức Chiến']
date: 1631746973
title: "ip rule, TLDR Pages"
description: "ip rule, IP routing policy database management."
categories: "linux"
---
> More information: <https://man7.org/linux/man-pages/man8/ip-rule.8.html>.

- Display the routing policy:

```bash
ip rule show|list
```

- Add a new rule based on packet source addresses:

```bash
sudo ip rule add from 192.168.178.2/32
```

- Add a new rule based on packet destination addresses:

```bash
sudo ip rule add to 192.168.178.2/32
```

- Delete a rule based on packet source addresses:

```bash
sudo ip rule delete from 192.168.178.2/32
```

- Delete a rule based on packet destination addresses:

```bash
sudo ip rule delete to 192.168.178.2/32
```

- Flush all deleted rules:

```bash
ip rule flush
```

- Save all rules to a file:

```bash
ip rule save > path/to/ip_rules.dat
```

- Restore all rules from a file:

```bash
ip rule restore < path/to/ip_rules.dat
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Nguyễn Đức Chiến](mailto:nobi@nobidev.com) | ip-rule: add page (#6504) | 2021-09-16T01:02:53 | [3447744e09e4](https://github.com/tldr-pages/tldr/commit/3447744e09e4a415cc6fd759ae9558f0f1c05948)

