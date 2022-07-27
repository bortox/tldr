---
author: ['Marco Bonelli', 'Proscream']
date: 1574435377
title: "ansible-galaxy, TLDR Pages"
description: "ansible-galaxy, 수용 가능한 역할 생성 및 관리."
categories: "common"
---
> 더 많은 정보: <https://docs.ansible.com/ansible/latest/cli/ansible-galaxy.html>.

- 역할 설치:

```bash
ansible-galaxy install 사용자이름.역할_
```

- 역할 제거:

```bash
ansible-galaxy remove 사용자이름.역할_이름
```

- 설치된 역할 리스트:

```bash
ansible-galaxy list
```

- 주어진 역할에 대해 검색:

```bash
ansible-galaxy search 역할_이름
```

- 새로운 역할 생성:

```bash
ansible-galaxy init 역할_이름
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Marco Bonelli](mailto:mebeim@users.noreply.github.com) | multiple pages: fix whitespace in Korean pages (#3603) | 2019-11-22T16:09:37 | [503e5f030cad](https://github.com/tldr-pages/tldr/commit/503e5f030cada020dd32b7d2bef431e2e8b5b2d8)
[Proscream](mailto:proscream@naver.com) | multiple pages: add Korean Translation (#3549) | 2019-11-19T18:13:49 | [5dfacef13066](https://github.com/tldr-pages/tldr/commit/5dfacef1306610247597b34374d3b62d41bd2f6f)

