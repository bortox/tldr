---
author: ['Marco Bonelli', 'Proscream', 'marchersimon']
date: 1618756407
title: "arp"
description: "arp, 시스템의 ARP 캐시 표시 및 조작."
categories: "common"
---
> 더 많은 정보: <https://manned.org/arp>.

- 현재 arp 테이블을 보여줍니다:

```bash
arp -a
```

- 전체 캐시 삭제:

```bash
sudo arp -a -d
```

- 특정 엔트리 삭제:

```bash
arp -d address
```

- 엔트리 생성:

```bash
arp -s address mac_address
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[marchersimon](mailto:marchersimon@zohomail.eu) | replace `man.archlinux.org` with `manned.org` | 2021-04-18T16:33:27 | [9abb079afb69](https://github.com/tldr-pages/tldr/commit/9abb079afb6972f3de61a30e1b3fb849ad4b68d9)
[marchersimon](mailto:marchersimon@zohomail.eu) | arp: add link | 2021-04-18T16:33:27 | [f06702a5bcc3](https://github.com/tldr-pages/tldr/commit/f06702a5bcc36ee9323d8e467b27e65ed111ef23)
[Marco Bonelli](mailto:mebeim@users.noreply.github.com) | multiple pages: fix whitespace in Korean pages (#3603) | 2019-11-22T16:09:37 | [503e5f030cad](https://github.com/tldr-pages/tldr/commit/503e5f030cada020dd32b7d2bef431e2e8b5b2d8)
[Proscream](mailto:proscream@naver.com) | multiple pages : Add Korean Translation (#3560) | 2019-11-14T02:44:51 | [4f797eb4ef82](https://github.com/tldr-pages/tldr/commit/4f797eb4ef827d22f1001a95c5eca8f03aebddc8)

