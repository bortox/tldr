---
author: ['Schneider', 'lch7167', 'bl-ue']
date: 1610462196
title: "bosh"
description: "bosh, bosh 디렉터를 배치 및 관리하기 위한 커맨드라인 도구."
categories: "common"
---
> 더 많은 정보: <https://bosh.io/docs/cli-v2/>.

- 디렉터의 로컬 별칭 생성:

```bash
bosh alias-env 환경명 -e ip_주소|url --ca-cert ca_증명서
```

- 환경 나열:

```bash
bosh environments
```

- 디렉터에 로그인:

```bash
bosh login -e 환경
```

- 배포 목록 나열:

```bash
bosh -e 환경 deployments
```

- 가상 머신 환경 나열:

```bash
bosh -e 환경 vms -d 전개
```

- 가상 머신의 ssh:

```bash
bosh -e 환경 ssh 가상머신 -d 전개
```

- stemcell 업로드:

```bash
bosh -e 환경 upload-stemcell stemcell_파일|url
```

- 현재 클라우드 구성 표시:

```bash
bosh -e 환경 cloud-config
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | multiple pages: normalize line endings from CRLF to LF | 2021-01-12T15:36:36 | [567dc4ce0663](https://github.com/tldr-pages/tldr/commit/567dc4ce0663231ea1b8b9533b327094eb82ba1f)
[Schneider](mailto:lucas.schneider@sap.com) | multiple ch pages: remove trailing whitespace | 2020-03-12T20:52:09 | [310c1e1f7607](https://github.com/tldr-pages/tldr/commit/310c1e1f7607c67e5651e4d3c118a43029639285)
[lch7167](mailto:youngsj69@gmail.com) | multiple pages (boot to bup): add korean translation (#3587) | 2019-11-19T18:21:58 | [0f1332a5d517](https://github.com/tldr-pages/tldr/commit/0f1332a5d517f703c15b54fe39b4f23f77505e7f)

