---
author: ['JJByun', 'Lucas Gabriel Schneider']
date: 1612112718
title: "clamscan"
description: "clamscan, 바이러스 검사를 하는 줄 명령어."
categories: "common"
---
> 더 많은 정보: <https://www.clamav.net>.

- 약점이 있는 파일을 검사합니다:

```bash
clamscan 경로/파일
```

- 특정 디렉토리의 모든 파일을 재귀적으로 검사합니다:

```bash
clamscan -r 경로/디렉토리
```

- stdin 으로부터 데이터를 검사합니다:

```bash
명령어 | clamscan -
```

- 바이러스 데이터베이스 파일 또는 파일 디렉토리 지정합니다:

```bash
clamscan --database 경로/데이터베이스_파일_혹은_디렉토리
```

- 현재 디렉토리를 검색하고 감염된 파일만 출력합니다:

```bash
clamscan --infected
```

- 검사한 리포트를 로그 파일로 내보냅니다:

```bash
clamscan --log 경로/로그파일
```

- 특정 디렉토리로 감염된 파일을 보냅니다:

```bash
clamscan --move 경로/감염된_디렉토리
```

- 감연된 파일을 제거합니다:

```bash
clamscan --remove yes
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | multiple pages: format technical tokens (#5119) Co-authored-by: bl-ue <54780737+bl-ue@users.noreply.github.com> Co-authored-by: [...] | 2021-01-31T18:05:18 | [a5fe31bc47ae](https://github.com/tldr-pages/tldr/commit/a5fe31bc47aece3efa5e66b52b3cf384f27d5d72)
[JJByun](mailto:jd0909@naver.com) | multiple pages : Add Korean Translation (#3583) * Translation-ko chsh.md cksum.md clamscan.md clang.md clear.md clementine.md cloc.md [...] | 2019-11-24T20:33:52 | [1c78b9e10694](https://github.com/tldr-pages/tldr/commit/1c78b9e10694d378aa40b6236450be14a3ef6a21)

