---
author: ['Marco Bonelli', 'lch7167', 'Lucas Gabriel Schneider', 'bl-ue', 'marchersimon']
date: 1633112881
title: "bash, TLDR Pages"
description: "bash, Bourne-Again SHell. `sh`-호환 명령 행 인터프리터."
categories: "common"
---
> 더 많은 정보: <https://gnu.org/software/bash/>.

- 대화식 쉘 시작:

```bash
bash
```

- 명령 실행:

```bash
bash -c "command"
```

- 파일에서 명령 실행:

```bash
bash file.sh
```

- 파일에서 명령 실행하고, 터미널에서 실행 된 모든 명령 기록:

```bash
bash -x file.sh
```

- 파일에서 명령 실행하고, 첫 번째 에러에서 중지:

```bash
bash -e file.sh
```

- stdin에서 명령 실행:

```bash
bash -s
```

- bash의 버전 정보 출력 (`echo $BASH_VERSION`을 사용하여 버전 문자열만 표시):

```bash
bash --version
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: sync more information links in translations (#6537) | 2021-10-01T20:28:01 | [642dbf2e972e](https://github.com/tldr-pages/tldr/commit/642dbf2e972e388fab8c84ba3b4685fb862b6454)
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | multiple pages: format technical tokens (#5119) Co-authored-by: bl-ue <54780737+bl-ue@users.noreply.github.com> Co-authored-by: [...] | 2021-01-31T18:05:18 | [a5fe31bc47ae](https://github.com/tldr-pages/tldr/commit/a5fe31bc47aece3efa5e66b52b3cf384f27d5d72)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | multiple pages: normalize "more information" labels (#5140) | 2021-01-15T18:24:49 | [c59f12aa9f55](https://github.com/tldr-pages/tldr/commit/c59f12aa9f55d85612ba22e4da86db293ff76977)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | multiple pages: normalize line endings from CRLF to LF | 2021-01-12T15:36:36 | [567dc4ce0663](https://github.com/tldr-pages/tldr/commit/567dc4ce0663231ea1b8b9533b327094eb82ba1f)
[Marco Bonelli](mailto:mebeim@users.noreply.github.com) | Add trailing newline to Korean pages (#3573) | 2019-11-15T16:59:10 | [07fab14d0e7b](https://github.com/tldr-pages/tldr/commit/07fab14d0e7b61291e76cd880594984bbc3e60e5)
[lch7167](mailto:youngsj69@gmail.com) | multiple pages: add korean translation (#3548) | 2019-11-12T22:17:52 | [a451d973e85d](https://github.com/tldr-pages/tldr/commit/a451d973e85daf798ecab99ce2a7937727a934da)

