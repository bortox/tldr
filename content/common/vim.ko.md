---
author: ['Choi Young-jin']
date: 1649332153
title: "vim, TLDR Pages"
description: "vim, Vim (Vi IMproved)는 커맨드 라인 텍스트 에디터로 다양한 종류의 텍스트 조작을 위해 여러 모드를 지원합니다."
categories: "common"
---
> `i` 를 눌러 입력 모드로 들어가고, `<Esc>` 를 눌러 Vim 명령어를 입력할 수 있는 일반 모드로 들어갑니다.

> 더 많은 정보: <https://www.vim.org>.

- 파일 열기:

```bash
vim 파일/의/경로
```

- 지정된 줄 번호에서 파일 열기:

```bash
vim +줄 번호 파일/의/경로
```

- Vim 메뉴얼 보기:

```bash
:help<Enter>
```

- 저장하고 종료:

```bash
:wq<Enter>
```

- 실행취소:

```bash
u
```

- 파일에서 패턴 검색 (`n`/`N` 을 눌러 다음/이전 항목으로 이동):

```bash
/검색할_패턴<Enter>
```

- 전체 파일에서 정규식 대체 수행:

```bash
:%s/정규식_표현/바꿀_문자열/g<Enter>
```

- 줄 번호 표시:

```bash
:set nu<Enter>
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Choi Young-jin](mailto:amateur.toss@gmail.com) | nc, telnet, vim: add Korean translation (#7960) | 2022-04-07T13:49:13 | [dc7bd7365399](https://github.com/tldr-pages/tldr/commit/dc7bd7365399837466c7f78637939756109f672b)

