---
author: ['sooohka']
date: 1633336054
title: "rm"
description: "rm, 파일 혹은 폴더를 삭제."
categories: "common"
---
> 더 많은 정보: <https://www.gnu.org/software/coreutils/rm>.

- 임의의 경로에서 파일을 제거:

```bash
rm 파일의/경로 다른/파일의/경로
```

- 재귀적으로 폴더와 그 폴더내의 하위폴더들을 모두 제거:

```bash
rm -r 폴더의/경로
```

- 강제로 폴더를 제거, 확인절차와 에러메시지를 띄우지 않음:

```bash
rm -rf 폴더의/경로
```

- 여라개의 파일을 하나씩 확인받으면서 제거:

```bash
rm -i 파일들
```

- 상세화면과 함께 파일을 제거, 삭제된 파일에 대해 메시지를 출력함:

```bash
rm -v 폴더의/경로/*
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[sooohka](mailto:shkorea1004@gmail.com) | rm: add Korean translation (#6729) | 2021-10-04T10:27:34 | [d8ddf742dfe6](https://github.com/tldr-pages/tldr/commit/d8ddf742dfe68c7a70bfa4383f518a757f85b949)

