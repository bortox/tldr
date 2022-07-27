---
author: ['Jonathan Reyes', 'bl-ue', 'Proscream']
date: 1643311827
title: "dig, TLDR Pages"
description: "dig, DNS 조회 유틸리티."
categories: "common"
---
> 더 많은 정보: <https://manned.org/dig>.

- 호스트이름과 관련된 IP 조회하기 (A records):

```bash
dig +short example.com
```

- 주어진 도메인 이름과 관련된 메일 서버 조회하기 (MX record):

```bash
dig +short example.com MX
```

- 주어진 도메인 이름에 대한 모든 유형의 레코드들 가져오기:

```bash
dig example.com ANY
```

- 쿼리할 대체 DNS 서버를 지정하기:

```bash
dig @8.8.8.8 example.com
```

- IP 주소에서 역방향 DNS 조회하기 (PTR record):

```bash
dig -x 8.8.8.8
```

- 영역에 대해 권한있는 이름 서버들을 찾고 SOA 레코드들 표시하기:

```bash
dig +nssearch example.com
```

- 반복적인 쿼리들을 수행하고 도메인 이름을 분석하기 위해 전체 추적 경로를 표시하기:

```bash
dig +trace example.com
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Jonathan Reyes](mailto:jreyes33@users.noreply.github.com) | dig: fix more information link (#7724) | 2022-01-27T20:30:27 | [cbd3214b25ef](https://github.com/tldr-pages/tldr/commit/cbd3214b25ef91e2590438cc9669c02f28720ce8)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | *: trim multiple spaces, fix line endings | 2021-04-04T01:44:24 | [04dd546e2de7](https://github.com/tldr-pages/tldr/commit/04dd546e2de7f59f40a867acca6f46b0dc8ea9b4)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | dig: add more info link to Korean translation | 2021-03-13T22:00:12 | [b2532c6b507b](https://github.com/tldr-pages/tldr/commit/b2532c6b507b31a39994b4d8ee524c783c0b7f16)
[Proscream](mailto:proscream@naver.com) | dig: Add Korean Translation (#3731) | 2020-01-05T19:03:38 | [72fce08ef678](https://github.com/tldr-pages/tldr/commit/72fce08ef67853d9c010deeb15cde53350651858)

