---
author: ['Chanho Lee']
date: 1635017217
title: "echo, TLDR Pages"
description: "echo, 주어진 인자들을 출력한다."
categories: "common"
---
> 더 많은 정보: <https://www.gnu.org/software/coreutils/echo>.

- 텍스트 메시지를 출력한다. 참고: 따옴표는 선택 사항:

```bash
echo "Hello World"
```

- 환경 변수가 있는 메시지 출력하기:

```bash
echo "My path is $PATH"
```

- 끝에 줄바꿈 없이 메시지 출력하기:

```bash
echo -n "Hello World"
```

- 파일에 메시지 추가하기:

```bash
echo "Hello World" >> file.txt
```

- 백슬래시 이스케이프 (특수문자)의 해석을 가능하게 하기:

```bash
echo -e "Column 1\tColumn 2"
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Chanho Lee](mailto:ibear6954@gmail.com) | echo: add Korean translation (#7045) | 2021-10-23T21:26:57 | [6da5089d9d84](https://github.com/tldr-pages/tldr/commit/6da5089d9d842dc9da60baa484b0e56c13cee8d2)

