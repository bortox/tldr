---
author: ['Marco Bonelli', 'lch7167', 'bl-ue', 'marchersimon']
date: 1633112881
title: "bat, TLDR Pages"
description: "bat, 파일들을 출력하고 연결. 구문 강조와 Git 통합을 가진`cat`클론."
categories: "common"
---
> 더 많은 정보: <https://github.com/sharkdp/bat>.

- 파일 내용을 표준 출력으로 출력:

```bash
bat file
```

- 여러 파일을 대상 파일에 연결:

```bash
bat file1 file2 > target_file
```

- 대상 파일에 여러 파일을 추가:

```bash
bat file1 file2 >> target_file
```

- 모든 출력 라인 번호 매기기:

```bash
bat -n file
```

- json파일 구문 강조:

```bash
bat --language json file.json
```

- 지원되는 모든 언어 표시:

```bash
bat --list-languages
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: sync more information links in translations (#6537) | 2021-10-01T20:28:01 | [642dbf2e972e](https://github.com/tldr-pages/tldr/commit/642dbf2e972e388fab8c84ba3b4685fb862b6454)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | multiple pages: normalize line endings from CRLF to LF | 2021-01-12T15:36:36 | [567dc4ce0663](https://github.com/tldr-pages/tldr/commit/567dc4ce0663231ea1b8b9533b327094eb82ba1f)
[Marco Bonelli](mailto:mebeim@users.noreply.github.com) | Add trailing newline to Korean pages (#3573) | 2019-11-15T16:59:10 | [07fab14d0e7b](https://github.com/tldr-pages/tldr/commit/07fab14d0e7b61291e76cd880594984bbc3e60e5)
[lch7167](mailto:youngsj69@gmail.com) | multiple pages: add korean translation (#3548) | 2019-11-12T22:17:52 | [a451d973e85d](https://github.com/tldr-pages/tldr/commit/a451d973e85daf798ecab99ce2a7937727a934da)

