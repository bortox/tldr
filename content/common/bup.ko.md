---
author: ['lch7167', 'bl-ue']
date: 1610462196
title: "bup, TLDR Pages"
description: "bup, Git 팩 파일 형식을 기반으로 하는 백업 시스템, 빠른 증분 저장 및. 전역 중복 제거 기능 제공."
categories: "common"
---
> 더 많은 정보: <https://github.com/bup/bup>.

- 지정된 로컬 디렉토리에서 백업 저장소 초기화:

```bash
bup -d 저장소/의/경로 init
```

- 백업을 수행하기 전에 지정된 디렉토리 준비:

```bash
bup -d 저장소/의/경로 index 디렉토리/의/경로
```

- 저장소에 디렉토리 백업:

```bash
bup -d 저장소/의/경로 save -n 백업명 디렉토리/의/경로
```

- 현재 저장소에 저장된 백업 스냅샷 표시:

```bash
bup -d 저장소/의/경로 ls
```

- 특정 백업 스냅샷을 목적 디렉토리에 복원:

```bash
bup -d 저장소/의/경로 restore -C 타겟_디렉토리/의/경로 백업명
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | multiple pages: normalize line endings from CRLF to LF | 2021-01-12T15:36:36 | [567dc4ce0663](https://github.com/tldr-pages/tldr/commit/567dc4ce0663231ea1b8b9533b327094eb82ba1f)
[lch7167](mailto:youngsj69@gmail.com) | multiple pages (boot to bup): add korean translation (#3587) | 2019-11-19T18:21:58 | [0f1332a5d517](https://github.com/tldr-pages/tldr/commit/0f1332a5d517f703c15b54fe39b4f23f77505e7f)

