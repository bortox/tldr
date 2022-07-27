---
author: ['lch7167', 'Dario Vladović', 'bl-ue', 'marchersimon']
date: 1617292466
title: "cp, TLDR Pages"
description: "cp, 파일 및 디렉토리 복사."
categories: "common"
---
> 더 많은 정보: <https://www.gnu.org/software/coreutils/cp>.

- 파일을 다른 위치로 복사:

```bash
cp 파일.ext/의/경로 복사본.ext/의/경로
```

- 파일 이름을 유지하면서 파일을 다른 디렉토리에 복사:

```bash
cp 파일.ext/의/경로 타겟_부모_디렉토리/의/경로
```

- 디렉토리의 내용을 다른 위치에 재귀적으로 복사(대상이 존재하면 디렉토리가 그 안에 복사됨):

```bash
cp -r 디렉토리/의/경로 복사본/의/경로
```

- 상세모드에서 디렉토리를 재귀적으로 복사(파일이 복사 될 때 표시됨):

```bash
cp -vr 디렉토리/의/경로 복사본/의/경로
```

- 대화식 모드에서 텍스트 파일을 다른 위치로 복사(덮어 쓰기 전에 사용자에게 일러줌):

```bash
cp -i *.txt 타겟_디렉토리/의/경로
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Dario Vladović](mailto:d.vladimyr@gmail.com) | coreutils*: use short more info links (#5658) | 2021-04-01T17:54:26 | [4830093903f6](https://github.com/tldr-pages/tldr/commit/4830093903f66ccf3ebbc2ecf477286e45edac59)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | cp: add more information link (#5556) | 2021-03-30T12:30:03 | [ad46ebe87a57](https://github.com/tldr-pages/tldr/commit/ad46ebe87a578bcb5e61d26addcf1bdfe287d75f)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | multiple pages: normalize line endings from CRLF to LF | 2021-01-12T15:36:36 | [567dc4ce0663](https://github.com/tldr-pages/tldr/commit/567dc4ce0663231ea1b8b9533b327094eb82ba1f)
[lch7167](mailto:youngsj69@gmail.com) | multiple pages(cp to cradle-elastic): add korean translation (#3607) | 2019-11-26T10:52:56 | [bd07a73beb01](https://github.com/tldr-pages/tldr/commit/bd07a73beb0168939d441cd008f17b80775a9ead)

