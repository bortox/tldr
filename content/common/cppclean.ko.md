---
author: ['lch7167', 'bl-ue', 'Lucas Gabriel Schneider']
date: 1612112718
title: "cppclean"
description: "cppclean, C++ 프로젝트에서 사용하지 않는 코드 찾기."
categories: "common"
---
> 더 많은 정보: <https://github.com/myint/cppclean>.

- 프로젝트 디렉토리에서 실행:

```bash
cppclean 프로젝트/의/경로
```

- 헤더가 `inc1/` 및 `inc2/` 디렉토리에 있는 프로젝트에서 실행:

```bash
cppclean 프로젝트/의/경로 --include-path=inc1 --include-path=inc2
```

- 특정 팡리 `main.cpp`에서 실행:

```bash
cppclean main.cpp
```

- `build`디렉토리를 제외한 현재 디렉토리에서 실행:

```bash
cppclean . --exclude=build
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | multiple pages: format technical tokens (#5119) Co-authored-by: bl-ue <54780737+bl-ue@users.noreply.github.com> Co-authored-by: [...] | 2021-01-31T18:05:18 | [a5fe31bc47ae](https://github.com/tldr-pages/tldr/commit/a5fe31bc47aece3efa5e66b52b3cf384f27d5d72)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | multiple pages: normalize line endings from CRLF to LF | 2021-01-12T15:36:36 | [567dc4ce0663](https://github.com/tldr-pages/tldr/commit/567dc4ce0663231ea1b8b9533b327094eb82ba1f)
[lch7167](mailto:youngsj69@gmail.com) | multiple pages(cp to cradle-elastic): add korean translation (#3607) | 2019-11-26T10:52:56 | [bd07a73beb01](https://github.com/tldr-pages/tldr/commit/bd07a73beb0168939d441cd008f17b80775a9ead)

