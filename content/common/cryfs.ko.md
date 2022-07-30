---
author: ['lch7167', 'bl-ue']
date: 1610462196
title: "cryfs"
description: "cryfs, 클라우드용 암호화 파일 시스템."
categories: "common"
---
> 더 많은 정보: <https://www.cryfs.org/>.

- 암호화 된 파일 시스템 마운트. 초기화 마법사는 처음 실행될 때 시작:

```bash
cryfs cipher_dir/의/경로 마운트_포인트/의/경로
```

- 암호화 된 파일 시스템 마운트 해제:

```bash
cryfs-unmount 마운트_포인트/의/경로
```

- 10분 동안 활동이 없으면 자동으로 마운트 해제:

```bash
cryfs --unmount-idle 10 cipher_dir/의/경로 마운트_포인트/의/경로
```

- 지원되는 암호 목록 표시:

```bash
cryfs --show-ciphers
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | multiple pages: normalize line endings from CRLF to LF | 2021-01-12T15:36:36 | [567dc4ce0663](https://github.com/tldr-pages/tldr/commit/567dc4ce0663231ea1b8b9533b327094eb82ba1f)
[lch7167](mailto:youngsj69@gmail.com) | multiple pages(cradle-install to cryfs): add korean translation (#3608) | 2019-11-24T21:02:01 | [9e178edb8e8e](https://github.com/tldr-pages/tldr/commit/9e178edb8e8e6f08faaee69479fdedc424453333)

