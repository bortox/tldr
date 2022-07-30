---
author: ['Proscream', 'marchersimon']
date: 1618756407
title: "apg"
description: "apg, 임의로 복잡한 랜덤 암호를 만듭니다."
categories: "common"
---
> 더 많은 정보: <https://manned.org/apg>.

- 임의 비밀번호 생성 (기본 비밀번호 길이는 8):

```bash
apg
```

- 1개 이상의 기호(S), 1개의 숫자(N), 1개의 대문자(C), 1개의 소문자(L) 로 비밀번호 생성:

```bash
apg -M SNCL
```

- 16개 글자의 비밀번호 생성:

```bash
apg -m 16
```

- 최대 길이가 16인 비밀번호 생성:

```bash
apg -x 16
```

- 사전에 나타나지 않는 암호를 생성(사전 파일을 제공해야함):

```bash
apg -r 디렉토리_파일
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[marchersimon](mailto:marchersimon@zohomail.eu) | replace `man.archlinux.org` with `manned.org` | 2021-04-18T16:33:27 | [9abb079afb69](https://github.com/tldr-pages/tldr/commit/9abb079afb6972f3de61a30e1b3fb849ad4b68d9)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | Apply suggestions from code review Co-authored-by: Axel Navarro <navarroaxel@gmail.com> Co-authored-by: bl-ue <54780737+bl- [...] | 2021-04-18T16:33:27 | [a8cbf084db1c](https://github.com/tldr-pages/tldr/commit/a8cbf084db1c27995da74db5833681eaea87dbfb)
[marchersimon](mailto:marchersimon@zohomail.eu) | apg: edit link | 2021-04-18T16:33:27 | [ec6a3682f0fe](https://github.com/tldr-pages/tldr/commit/ec6a3682f0feaea05c28b65ddac54d395b32a284)
[marchersimon](mailto:marchersimon@zohomail.eu) | apg: add link | 2021-04-18T16:33:27 | [d5cbcd6fbca3](https://github.com/tldr-pages/tldr/commit/d5cbcd6fbca3201f690a82f177faf6679349e803)
[Proscream](mailto:proscream@naver.com) | multiple pages : Add Korean Translation (#3553) | 2019-11-19T18:15:13 | [cb340e934155](https://github.com/tldr-pages/tldr/commit/cb340e93415596ec3e67bcb079a96b0dc5b331a7)

