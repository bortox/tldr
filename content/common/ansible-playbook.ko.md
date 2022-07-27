---
author: ['Marco Bonelli', 'Proscream']
date: 1574435377
title: "ansible-playbook, TLDR Pages"
description: "ansible-playbook, SSH를 통해 원격 머신에서 playbook에 정의된 작업 실행."
categories: "common"
---
> 더 많은 정보: <https://docs.ansible.com/ansible/latest/cli/ansible-playbook.html>.

- playbook에서 작업 실행:

```bash
ansible-playbook playbook
```

- 사용자 정의 호스트 인벤토리를 포함한 playbook에서 작업 실행:

```bash
ansible-playbook playbook -i 인벤토리_파일
```

- 명령어 라인을 통해 정의된 추가 변수를 사용하여 playbook에서 작업 실행:

```bash
ansible-playbook playbook -e "변수1=값1 변수2=값2"
```

- json 파일에 정의된 추가 변수를 사용하여 playbook에서 작업 실행:

```bash
ansible-playbook playbook -e "@변수.json"
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Marco Bonelli](mailto:mebeim@users.noreply.github.com) | multiple pages: fix whitespace in Korean pages (#3603) | 2019-11-22T16:09:37 | [503e5f030cad](https://github.com/tldr-pages/tldr/commit/503e5f030cada020dd32b7d2bef431e2e8b5b2d8)
[Proscream](mailto:proscream@naver.com) | multiple pages : Add Korean Translation (#3553) | 2019-11-19T18:15:13 | [cb340e934155](https://github.com/tldr-pages/tldr/commit/cb340e93415596ec3e67bcb079a96b0dc5b331a7)

