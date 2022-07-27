---
author: ['dmakth', 'Lucas Gabriel Schneider', 'Dario Vladović', 'marchersimon']
date: 1617292466
title: "cut, TLDR Pages"
description: "cut, stdin 혹은 파일에서 출력 필드를 자른다."
categories: "common"
---
> 더 많은 정보: <https://www.gnu.org/software/coreutils/cut>.

- stdin의 각 라인에 첫번째 16개의 문자를 자르기:

```bash
cut -c 1-16
```

- 지정된 파일의 각 라인의 첫번째 16개 문자를 자르기:

```bash
cut -c 1-16 파일
```

- 3번째 문자 부터 각 라인의 끝까지 모든 문자를 자르기:

```bash
cut -c 3-
```

- `:` 을 필드 구분 기호로 사용하여 각 라인의 5번째 필드를 자르기(기본 구분 기호 : 탭):

```bash
cut -d':' -f5
```

- `;` 을 구분 기호로 사용하여 각 라인의 2번째와 10번째 필드를 자르기:

```bash
cut -d';' -f2,10
```

- 공백을 구분 기호로 사용하여 각 라인의 끝까지 필드 3을 자르기:

```bash
cut -d' ' -f3-
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Dario Vladović](mailto:d.vladimyr@gmail.com) | coreutils*: use short more info links (#5658) | 2021-04-01T17:54:26 | [4830093903f6](https://github.com/tldr-pages/tldr/commit/4830093903f66ccf3ebbc2ecf477286e45edac59)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | cut: add link (#5576) | 2021-03-30T13:39:27 | [f311aa47f394](https://github.com/tldr-pages/tldr/commit/f311aa47f394998f831ebd4af66733b85cc9c08a)
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | multiple pages: format technical tokens (#5119) Co-authored-by: bl-ue <54780737+bl-ue@users.noreply.github.com> Co-authored-by: [...] | 2021-01-31T18:05:18 | [a5fe31bc47ae](https://github.com/tldr-pages/tldr/commit/a5fe31bc47aece3efa5e66b52b3cf384f27d5d72)
[dmakth](mailto:49394293+dmakth@users.noreply.github.com) | Mutiple pages: add Korean translation (#3594) Add Korean translation for the following common pages: - csvpy - csvsort - csvstat - [...] | 2019-11-22T09:10:17 | [61fa29d29fd0](https://github.com/tldr-pages/tldr/commit/61fa29d29fd0c99587f5d0069bb7587567db3c32)

