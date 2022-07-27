---
author: ['Schneider', 'lch7167', 'bl-ue', 'marchersimon']
date: 1633112881
title: "bitcoin-cli, TLDR Pages"
description: "bitcoin-cli, RPC 호출을 통해 비트코인 데몬과 상호 작용하는 커맨드라인 클라이언트.`bitcoin.conf`에 정의된 구성 사용."
categories: "common"
---
> 더 많은 정보: <https://en.bitcoin.it/wiki/Running_Bitcoin#Command-line_arguments>.

- 지정된 주소로 트랜잭션 전송:

```bash
bitcoin-cli sendtoaddress "주소" 양
```

- 하나 이상의 블록 생성:

```bash
bitcoin-cli generate 블록_갯수
```

- wallet에 대한 고급 정보 출력:

```bash
bitcoin-cli getwalletinfo
```

- 보내지지 않은 모든 트랜잭션의 출력 나열:

```bash
bitcoin-cli listunspent
```

- wallet 정보를 텍스트 파일로 출력:

```bash
bitcoin-cli dumpwallet "파일/의/경로"
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: sync more information links in translations (#6537) | 2021-10-01T20:28:01 | [642dbf2e972e](https://github.com/tldr-pages/tldr/commit/642dbf2e972e388fab8c84ba3b4685fb862b6454)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | multiple pages: normalize "more information" labels (#5140) | 2021-01-15T18:24:49 | [c59f12aa9f55](https://github.com/tldr-pages/tldr/commit/c59f12aa9f55d85612ba22e4da86db293ff76977)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | multiple pages: normalize line endings from CRLF to LF | 2021-01-12T15:36:36 | [567dc4ce0663](https://github.com/tldr-pages/tldr/commit/567dc4ce0663231ea1b8b9533b327094eb82ba1f)
[Schneider](mailto:lucas.schneider@sap.com) | multiple ch pages: remove trailing whitespace | 2020-03-12T20:52:09 | [310c1e1f7607](https://github.com/tldr-pages/tldr/commit/310c1e1f7607c67e5651e4d3c118a43029639285)
[lch7167](mailto:youngsj69@gmail.com) | multiple pages: add korean translation (#3564) | 2019-11-18T02:50:21 | [894df52f44af](https://github.com/tldr-pages/tldr/commit/894df52f44af2b32579b1009d539956058766205)

