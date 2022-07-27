---
author: ['marchersimon', 'Marco Bonelli', 'Choi Young-jin', 'Proscream']
date: 1649632199
title: "7za, TLDR Pages"
description: "7za, 높은 파일 압축률을 보여주는 파일 압축 프로그램."
categories: "common"
---
> 더 적은 압축 타입을 지원하지만, 크로스플랫폼인 점을 제외하면 `7z`과 유사합니다.

> 더 많은 정보: <https://www.7-zip.org>.

- 파일이나 디렉토리 압축하기:

```bash
7za a 경로/archived.7z 파일_혹은_디렉토리/의/경로
```

- 압축파일 암호화 (including file names):

```bash
7za a 경로/encrypted.7z -p비밀번호 -mhe=on 경로/archive.7z
```

- 기존 디렉토리 경로에 존재하는 7z 파일 추출:

```bash
7za x archive.7z
```

- 특정 디렉토리에 압축파일 추출:

```bash
7za x 경로/archive.7z -o아웃풋/의/경로
```

- stdout에 압축파일 추출:

```bash
7za x 경로/archive.7z -so
```

- 특정 압축 타입을 이용하여 추출하기:

```bash
7za a -tzip|gzip|bzip2|tar archived path/to/file_or_directory
```

- 압축 파일의 내용 리스트:

```bash
7za l 경로/archive.7z
```

- 사용가능한 압축 타입 리스트:

```bash
7za i
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Choi Young-jin](mailto:amateur.toss@gmail.com) | 2to3, 7za, 7zr, [, [[, aapt: add Korean translate (#7970) | 2022-04-11T01:09:59 | [14a5e6b02006](https://github.com/tldr-pages/tldr/commit/14a5e6b02006ec880b4133a9faac5afdf00ff62e)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: sync more information links in translations (#6537) | 2021-10-01T20:28:01 | [642dbf2e972e](https://github.com/tldr-pages/tldr/commit/642dbf2e972e388fab8c84ba3b4685fb862b6454)
[Marco Bonelli](mailto:mebeim@users.noreply.github.com) | multiple pages: fix whitespace in Korean pages (#3603) | 2019-11-22T16:09:37 | [503e5f030cad](https://github.com/tldr-pages/tldr/commit/503e5f030cada020dd32b7d2bef431e2e8b5b2d8)
[Marco Bonelli](mailto:mebeim@users.noreply.github.com) | Add trailing newline to Korean pages (#3573) | 2019-11-15T16:59:10 | [07fab14d0e7b](https://github.com/tldr-pages/tldr/commit/07fab14d0e7b61291e76cd880594984bbc3e60e5)
[Proscream](mailto:proscream@naver.com) | tldr : add korean translation (#3533) | 2019-11-11T02:15:51 | [13d5dd0ac848](https://github.com/tldr-pages/tldr/commit/13d5dd0ac84887e01524bca201c2b9199805418d)

