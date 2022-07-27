---
author: ['Marco Bonelli', 'bl-ue', 'Proscream']
date: 1617130649
title: "alias, TLDR Pages"
description: "alias, 명령 문자열로 대체되는 단어인 별칭 -- 작성."
categories: "common"
---
> 별칭은 셀의 구성 파일에 정의되어 있지 않으면 현재 쉘 세션으로 만료됩니다, 예 : `~/.bashrc`.

> 더 많은 정보: <https://tldp.org/LDP/abs/html/aliases.html>.

- 모든 별칭 리스트:

```bash
alias
```

- 일반 별칭 생성:

```bash
alias 단어="명령어"
```

- 주어진 별칭에 연관된 명령어:

```bash
alias 단어
```

- 별칭 명령어 제거:

```bash
unalias 단어
```

- `rm` 을 대화형 명령어로 전환:

```bash
alias rm="rm -i"
```

- `ls -a`의 지름길인 `la`생성:

```bash
alias la="ls -a"
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | alias: add more information link (#5644) | 2021-03-30T20:57:29 | [edd9c5a5dc32](https://github.com/tldr-pages/tldr/commit/edd9c5a5dc32839ecf45b50d02d0260b8032002e)
[Marco Bonelli](mailto:mebeim@users.noreply.github.com) | multiple pages: fix whitespace in Korean pages (#3603) | 2019-11-22T16:09:37 | [503e5f030cad](https://github.com/tldr-pages/tldr/commit/503e5f030cada020dd32b7d2bef431e2e8b5b2d8)
[Proscream](mailto:proscream@naver.com) | multiple pages: add Korean Translation (#3549) | 2019-11-19T18:13:49 | [5dfacef13066](https://github.com/tldr-pages/tldr/commit/5dfacef1306610247597b34374d3b62d41bd2f6f)

