---
author: ['Choi Young-jin', 'Proscream', 'marchersimon']
date: 1649632199
title: "7zr"
description: "7zr, 높은 파일압축률을 보여주는 압축 프로그램."
categories: "common"
---
> .7z파일들만을 지원하는 `7z`의 독립형 버전.

> 더 많은 정보: <https://www.7-zip.org>.

- 파일이나 디렉토리 압축하기:

```bash
7zr a 경로/archived.7z 경로/파일명_또는_디렉토리명
```

- 압축파일 암호화 (including file names):

```bash
7zr a 경로/encrypted.7z -p비밀번호 -mhe=on 경로/archive.7z
```

- 기존 디렉토리 경로에 존재하는 7z파일 추출하기:

```bash
7zr x archived.7z
```

- 특정 디렉토리에 압축파일 추출:

```bash
7zr x 경로/archive.7z -o아웃풋/의/경로
```

- stdout에 압축파일 추출:

```bash
7zr x 경로/archive.7z -so
```

- 압축 파일의 내용 리스트:

```bash
7zr l 경로/archived.7z
```

- 사용가능한 압축 타입 리스트:

```bash
7zr i
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Choi Young-jin](mailto:amateur.toss@gmail.com) | 2to3, 7za, 7zr, [, [[, aapt: add Korean translate (#7970) | 2022-04-11T01:09:59 | [14a5e6b02006](https://github.com/tldr-pages/tldr/commit/14a5e6b02006ec880b4133a9faac5afdf00ff62e)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: sync more information links in translations (#6537) | 2021-10-01T20:28:01 | [642dbf2e972e](https://github.com/tldr-pages/tldr/commit/642dbf2e972e388fab8c84ba3b4685fb862b6454)
[Proscream](mailto:proscream@naver.com) | multiple pages : Add Korean Translation (#3553) | 2019-11-19T18:15:13 | [cb340e934155](https://github.com/tldr-pages/tldr/commit/cb340e93415596ec3e67bcb079a96b0dc5b331a7)
[Proscream](mailto:proscream@naver.com) | multiple pages: add Korean Translation (#3549) | 2019-11-19T18:13:49 | [5dfacef13066](https://github.com/tldr-pages/tldr/commit/5dfacef1306610247597b34374d3b62d41bd2f6f)
[Proscream](mailto:proscream@naver.com) | tldr : add korean translation (#3533) | 2019-11-11T02:15:51 | [13d5dd0ac848](https://github.com/tldr-pages/tldr/commit/13d5dd0ac84887e01524bca201c2b9199805418d)

