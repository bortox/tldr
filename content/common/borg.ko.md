---
author: ['Schneider', 'lch7167', 'bl-ue']
date: 1610462196
title: "borg"
description: "borg, 중복제거 백업 도구. 파일시스템으로 마운트할 수 있는 로컬 또는 원격 저장소를 제작."
categories: "common"
---
> 더 많은 정보: <https://borgbackup.readthedocs.io/en/stable/usage/general.html>.

- (로컬) 저장소 초기화:

```bash
borg init /저장소_디렉토리/의/경로
```

- 디렉토리를 저장소에 백업하여, "Monday"라는 아카이브 생성:

```bash
borg create --progress /저장소_디렉토리/의/경로::Monday /소스_디렉토리/의/경로
```

- 저장소의 모든 아카이브 나열:

```bash
borg list /저장소_디렉토리/의/경로
```

- *.ext 파일을 제외하고 원격 저장소의 "Monday" 아카이브에서 특정 디렉토리 추출:

```bash
borg extract user@host:/저장소_디렉토리/의/경로::Monday /타겟_디렉토리/의/경로 --exclude '*.ext'
```

- 7일이 지난 아카이브를 모두 삭제하고, 변경 사항을 나열하여 저장소 정리:

```bash
borg prune --keep-within 7d --list /저장소_디렉토리/의/경로
```

- 저장소를 FUSE 파일 시스템으로 마운트:

```bash
borg mount /저장소_디렉토리/의/경로::Monday /마운트포인트/의/경로
```

- 아카이브 작성에 대한 도움말 표시:

```bash
borg create --help
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | multiple pages: normalize line endings from CRLF to LF | 2021-01-12T15:36:36 | [567dc4ce0663](https://github.com/tldr-pages/tldr/commit/567dc4ce0663231ea1b8b9533b327094eb82ba1f)
[Schneider](mailto:lucas.schneider@sap.com) | multiple ch pages: remove trailing whitespace | 2020-03-12T20:52:09 | [310c1e1f7607](https://github.com/tldr-pages/tldr/commit/310c1e1f7607c67e5651e4d3c118a43029639285)
[lch7167](mailto:youngsj69@gmail.com) | multiple pages (boot to bup): add korean translation (#3587) | 2019-11-19T18:21:58 | [0f1332a5d517](https://github.com/tldr-pages/tldr/commit/0f1332a5d517f703c15b54fe39b4f23f77505e7f)

