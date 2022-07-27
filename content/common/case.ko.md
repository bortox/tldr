---
author: ['marchersimon', 'Proscream']
date: 1618756407
title: "case, TLDR Pages"
description: "case, 표현식의 값에 근거하여 분기."
categories: "common"
---
> 더 많은 정보: <https://manned.org/case>.

- 변수를 문자열 리터럴과 일치시켜 실행할 명령어 결정:

```bash
case $tocount in words) wc -w README; ;; lines) wc -l README; ;; esac
```

- 패턴을 |와 결합하고, *를 대비책 패턴으로 사용:

```bash
case $tocount in [wW]|words) wc -w README; ;; [lL]|lines) wc -l README; ;; *) echo "what?"; ;; esac
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[marchersimon](mailto:marchersimon@zohomail.eu) | replace `man.archlinux.org` with `manned.org` | 2021-04-18T16:33:27 | [9abb079afb69](https://github.com/tldr-pages/tldr/commit/9abb079afb6972f3de61a30e1b3fb849ad4b68d9)
[marchersimon](mailto:marchersimon@zohomail.eu) | case: add link | 2021-04-18T16:33:27 | [4d87a4e1a562](https://github.com/tldr-pages/tldr/commit/4d87a4e1a562f8aa1581c21aa263994d3c5078fa)
[Proscream](mailto:proscream@naver.com) | Multiple pages(calibredb to case) : Add Korean Translation (#3582) | 2019-11-19T18:19:13 | [8181c0c27ef2](https://github.com/tldr-pages/tldr/commit/8181c0c27ef2d2f85fdb7c07a4a0f0e02bf5a4d3)

