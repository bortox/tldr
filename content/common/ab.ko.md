---
author: ['bl-ue', 'Proscream', 'Marco Bonelli']
date: 1615671899
title: "ab"
description: "ab, 아파치 벤치마킹 도구."
categories: "common"
---
> 로드 테스트를 수행하는 가장 간단한 도구.

> 더 많은 정보: <https://httpd.apache.org/docs/current/programs/ab.html>.

- 주어진 URL에 대해 100개의 HTTP GET 요청 실행:

```bash
ab -n 100 url
```

- 지정된 URL에 대해 최대 10개의 요청을 동시에 처리하여 100개의 HTTP GET을 실행:

```bash
ab -n 100 -c 10 url
```

- 생존을 유지하며 사용:

```bash
ab -k url
```

- 벤치마킹에 사용될 최대 시간(초) 설정:

```bash
ab -t 60 url
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | ab: update grammar; update link (#5433) | 2021-03-13T22:44:59 | [8f2ed246f761](https://github.com/tldr-pages/tldr/commit/8f2ed246f7614df6e815b9eefae053a0f64df920)
[Marco Bonelli](mailto:mebeim@users.noreply.github.com) | multiple pages: fix whitespace in Korean pages (#3603) | 2019-11-22T16:09:37 | [503e5f030cad](https://github.com/tldr-pages/tldr/commit/503e5f030cada020dd32b7d2bef431e2e8b5b2d8)
[Marco Bonelli](mailto:mebeim@users.noreply.github.com) | Add trailing newline to Korean pages (#3573) | 2019-11-15T16:59:10 | [07fab14d0e7b](https://github.com/tldr-pages/tldr/commit/07fab14d0e7b61291e76cd880594984bbc3e60e5)
[Proscream](mailto:proscream@naver.com) | tldr : add korean translation (#3533) | 2019-11-11T02:15:51 | [13d5dd0ac848](https://github.com/tldr-pages/tldr/commit/13d5dd0ac84887e01524bca201c2b9199805418d)

