---
author: ['Marco Bonelli', 'Proscream', 'GermanS', 'marchersimon']
date: 1633112881
title: "ack"
description: "ack, 프로그래머에게 최적화된 grep과 같은 검색툴."
categories: "common"
---
> 더 많은 정보: <https://beyondgrep.com/documentation>.

- "foo"를 포함하고 있는 파일 검색:

```bash
ack foo
```

- 특정 타입의 파일 검색:

```bash
ack --ruby foo
```

- "foo"라는 용어와 일치하는 총 합을 계산:

```bash
ack -ch foo
```

- "foo"를 포함하고있는 파일의 이름과 각각 파일에서 일치하는 수를 표시:

```bash
ack -cl foo
```

- 모든 가능한 타입 리스트:

```bash
ack --help-types
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: sync more information links in translations (#6537) | 2021-10-01T20:28:01 | [642dbf2e972e](https://github.com/tldr-pages/tldr/commit/642dbf2e972e388fab8c84ba3b4685fb862b6454)
[GermanS](mailto:german.semenkov@gmail.com) | ack: fix typo (#4196) | 2020-07-16T23:33:06 | [ad248fb1170c](https://github.com/tldr-pages/tldr/commit/ad248fb1170c1bac38349a554cf3b37270747353)
[Marco Bonelli](mailto:mebeim@users.noreply.github.com) | multiple pages: fix whitespace in Korean pages (#3603) | 2019-11-22T16:09:37 | [503e5f030cad](https://github.com/tldr-pages/tldr/commit/503e5f030cada020dd32b7d2bef431e2e8b5b2d8)
[Marco Bonelli](mailto:mebeim@users.noreply.github.com) | Add trailing newline to Korean pages (#3573) | 2019-11-15T16:59:10 | [07fab14d0e7b](https://github.com/tldr-pages/tldr/commit/07fab14d0e7b61291e76cd880594984bbc3e60e5)
[Proscream](mailto:proscream@naver.com) | tldr : add korean translation (#3533) | 2019-11-11T02:15:51 | [13d5dd0ac848](https://github.com/tldr-pages/tldr/commit/13d5dd0ac84887e01524bca201c2b9199805418d)

