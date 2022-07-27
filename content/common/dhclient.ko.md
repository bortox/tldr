---
author: ['marchersimon', 'Proscream']
date: 1618869951
title: "dhclient, TLDR Pages"
description: "dhclient, DHCP 클라이언트."
categories: "common"
---
> 더 많은 정보: <https://manned.org/dhclient>.

- 'eht0' 인터페이스의 IP 주소 얻기:

```bash
sudo dhclient eth0
```

- 'eth0' 인터페이스의 IP 주소 해제하기:

```bash
sudo dhclient -r eth0
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[marchersimon](mailto:marchersimon@zohomail.eu) | add more information links | 2021-04-20T00:05:51 | [bc5d06ed1e1e](https://github.com/tldr-pages/tldr/commit/bc5d06ed1e1e112cfb368a38ae5918ef124cdc22)
[Proscream](mailto:proscream@naver.com) | dhclient: Add Korean Translation (#3679) | 2019-12-24T14:56:44 | [e7ae03409aa3](https://github.com/tldr-pages/tldr/commit/e7ae03409aa30f1abe29b26124253e260f906aaa)

