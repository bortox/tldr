---
author: ['Marco Bonelli', 'JJByun', 'marchersimon']
date: 1618756407
title: "complete, TLDR Pages"
description: "complete, 쉘 명령어에 자동 완성 인자를 제공합니다."
categories: "common"
---
> 더 많은 정보: <https://www.gnu.org/software/bash/manual/html_node/Programmable-Completion-Builtins.html>.

- 함수에 명령어 자동 완성 기능을 적용합니다:

```bash
complete -F 함수 명령어
```

- 다른 명령어에 명령어 자동 완성 기능을 적용합니다:

```bash
complete -C 자동완성_명령어 명령어
```

- 작성 완료된 단어에 공백을 추가하지 않고 자동 완성 기능을 적용합니다:

```bash
complete -o nospace -F 함수 명령어
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[marchersimon](mailto:marchersimon@zohomail.eu) | complete: add link | 2021-04-18T16:33:27 | [02f8ccffbede](https://github.com/tldr-pages/tldr/commit/02f8ccffbede5fe1feac284569e1f8a9ee917e09)
[Marco Bonelli](mailto:mebeim@users.noreply.github.com) | Add missing trailing newline to some Korean pages (#3633) | 2019-11-28T22:16:38 | [53af408ce5f2](https://github.com/tldr-pages/tldr/commit/53af408ce5f2cd186e88d32b54203109e890486c)
[JJByun](mailto:jd0909@naver.com) | mutiple pages(complete to consul-kv) : Add Korean Translation (#3596) | 2019-11-22T16:08:47 | [21c755e52ade](https://github.com/tldr-pages/tldr/commit/21c755e52ade9452392011d02ec34fbb1dfa4db5)

