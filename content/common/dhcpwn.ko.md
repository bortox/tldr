---
author: ['Proscream']
date: 1577195765
title: "dhcpwn"
description: "dhcpwn, DHCP IP 소진하는 공격을 테스트하고 로컬 DHCP 트래픽을 스니핑한다."
categories: "common"
---
> 더 많은 정보: <https://github.com/mschwager/dhcpwn>.

- 네트워크에 IP 요청들로 쇄도하기:

```bash
dhcpwn --interface 네트워크_인터페이스 flood --count 요청들의_수
```

- 로컬 DHCP 트래픽 스니핑하기:

```bash
dhcpwn --interface 네트워크_인터페이스 sniff
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Proscream](mailto:proscream@naver.com) | dhcpwn: Add Korean Translation (#3686) | 2019-12-24T14:56:05 | [44bd28d66020](https://github.com/tldr-pages/tldr/commit/44bd28d66020ed0a5f586cb3f48cba19e25c00d8)

