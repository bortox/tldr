---
author: ['Proscream', 'Seth Falco', 'Marco Bonelli']
date: 1648358715
title: "arping"
description: "arping, ARP 프로토콜을 사용하여 네트워크에서 호스트를 발견하고 탐색합니다."
categories: "common"
---
> MAC 주소 검색에 유용합니다.

> 더 많은 정보: <https://github.com/ThomasHabets/arping>.

- ARP 요청 패킷으로 호스트 ping 하기:

```bash
arping host_ip
```

- 특정 인터페이스의 호스트로 ping 하기:

```bash
arping -I interface host_ip
```

- 첫 응답을 한 호스트로 ping 하기:

```bash
arping -f host_ip
```

- 호스트에 특정 횟수 ping 하기:

```bash
arping -c count host_ip
```

- 브로드캐스트 ARP 요청 패킷을 통해 이웃 ARP 캐시 업데이트:

```bash
arping -U ip_to_broadcast
```

- 3초의 시간 제한을 사용하여 ARP 요청을 전송하여 네트워크에서 중복된 IP 주소를 탐지합니다:

```bash
arping -D -w 3 ip_to_check
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Seth Falco](mailto:seth@falco.fun) | *: normalize colons (#7913) | 2022-03-27T07:25:15 | [27ff55fc2eea](https://github.com/tldr-pages/tldr/commit/27ff55fc2eea445eb5216c3b1d934960539fc024)
[Marco Bonelli](mailto:mebeim@users.noreply.github.com) | multiple pages: fix whitespace in Korean pages (#3603) | 2019-11-22T16:09:37 | [503e5f030cad](https://github.com/tldr-pages/tldr/commit/503e5f030cada020dd32b7d2bef431e2e8b5b2d8)
[Marco Bonelli](mailto:mebeim@users.noreply.github.com) | Add missing trailing newline to some Korean pages. (#3575) | 2019-11-15T18:01:53 | [7f699a83abd0](https://github.com/tldr-pages/tldr/commit/7f699a83abd08868a78220fb3222aa455974fd2a)
[Proscream](mailto:proscream@naver.com) | multiple pages : Add Korean Translation (#3560) | 2019-11-14T02:44:51 | [4f797eb4ef82](https://github.com/tldr-pages/tldr/commit/4f797eb4ef827d22f1001a95c5eca8f03aebddc8)

