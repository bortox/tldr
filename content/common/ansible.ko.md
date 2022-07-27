---
author: ['Lucas Gabriel Schneider', 'Proscream']
date: 1612112718
title: "ansible, TLDR Pages"
description: "ansible, SSH를 통해 컴퓨터 그룹을 원격으로 관리."
categories: "common"
---
> `/etc/ansible/hosts` 파일을 사용하여 새 그룹/호스트를 추가하십시오.

> 더 많은 정보: <https://www.ansible.com/>.

- 그룹에 속한 호스트 목록:

```bash
ansible 그룹명 --list-hosts
```

- 핑 모듈을 호출하여 호스트 그룹 핑:

```bash
ansible 그룹명 -m ping
```

- 설정 모듈을 호출하여 호스트 그룹에 대한 사실 표시:

```bash
ansible 그룹명 -m setup
```

- 명령 모듈을 인수로 호출하여 호스트 그룹에서 명령어 실행:

```bash
ansible 그룹명 -m command -a '나의_명령어'
```

- 관리자 권한으로 명령어 실행:

```bash
ansible 그룹명 --become --ask-become-pass -m command -a '나의_명령어'
```

- 사용자 정의 인벤토리 파일을 사용하여 명령어 실행:

```bash
ansible 그룹 -i 인벤토리_파일 -m command -a '나의_명령어'
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | multiple pages: format technical tokens (#5119) Co-authored-by: bl-ue <54780737+bl-ue@users.noreply.github.com> Co-authored-by: [...] | 2021-01-31T18:05:18 | [a5fe31bc47ae](https://github.com/tldr-pages/tldr/commit/a5fe31bc47aece3efa5e66b52b3cf384f27d5d72)
[Proscream](mailto:proscream@naver.com) | multiple pages: add Korean Translation (#3549) | 2019-11-19T18:13:49 | [5dfacef13066](https://github.com/tldr-pages/tldr/commit/5dfacef1306610247597b34374d3b62d41bd2f6f)

