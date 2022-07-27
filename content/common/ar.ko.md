---
author: ['marchersimon', 'Proscream']
date: 1618756407
title: "ar, TLDR Pages"
description: "ar, 아카이브로부터 생성, 수정, 추출 (`.a`, `.so`, `.o`)."
categories: "common"
---
> 더 많은 정보: <https://manned.org/ar>.

- 보관소로부터 모든 멤버를 추출하기:

```bash
ar -x libfoo.a
```

- 보관소 멤버 리스트 보여주기:

```bash
ar -t libfoo.a
```

- 보관소로 파일을 대체하거나 추가하기:

```bash
ar -r libfoo.a foo.o bar.o baz.o
```

- object 파일 인덱스 삽입( `ranlib` 와 같은 기능입니다):

```bash
ar -s libfoo.a
```

- 파일 및 첨부된 객체 파일 색인을 사용하여 보관소에 작성:

```bash
ar -rs libfoo.a foo.o bar.o baz.o
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[marchersimon](mailto:marchersimon@zohomail.eu) | replace `man.archlinux.org` with `manned.org` | 2021-04-18T16:33:27 | [9abb079afb69](https://github.com/tldr-pages/tldr/commit/9abb079afb6972f3de61a30e1b3fb849ad4b68d9)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | Apply suggestions from code review Co-authored-by: bl-ue <54780737+bl-ue@users.noreply.github.com> | 2021-04-18T16:33:27 | [3c2cf700535c](https://github.com/tldr-pages/tldr/commit/3c2cf700535c96240fc4832e5c1e117c6e4b696d)
[marchersimon](mailto:marchersimon@zohomail.eu) | ar: add link | 2021-04-18T16:33:27 | [bc1219f3c90d](https://github.com/tldr-pages/tldr/commit/bc1219f3c90dc2328626e04ab6496ddd8f0405d3)
[Proscream](mailto:proscream@naver.com) | multiple pages : Add Korean Translation (#3560) | 2019-11-14T02:44:51 | [4f797eb4ef82](https://github.com/tldr-pages/tldr/commit/4f797eb4ef827d22f1001a95c5eca8f03aebddc8)

