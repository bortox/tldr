---
author: ['bl-ue', 'Proscream']
date: 1612369364
title: "atoum"
description: "atoum, PHP를 위한 단순하고 현대적이며 직관적인 단위 테스트 프레임워크."
categories: "common"
---
> 더 많은 정보: <http://atoum.org>.

- 설정 파일 초기화:

```bash
atoum --init
```

- 모든 테스트 실행:

```bash
atoum
```

- 특정 설정 파일을 사용한 테스트 실행:

```bash
atoum -c 경로/파일명
```

- 특정 테스트파일 실행:

```bash
atoum -f 경로/파일명
```

- 특정 테스트 디렉토리 실행:

```bash
atoum -d 경로/디렉토리명
```

- 특정 namespace 아래 있는 모든 테스트 실행:

```bash
atoum -ns namespace
```

- 특정 태그를 갖고 테스트 실행:

```bash
atoum -t 태그
```

- 테스트를 실행하기 전에 사용자 지정 부트스트랩 파일을 로드:

```bash
atoum --bootstrap-file 경로/파일명
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | multiple pages: ensure exactly one colon at the end of example descriptions (#5214) | 2021-02-03T17:22:44 | [d28035c980bd](https://github.com/tldr-pages/tldr/commit/d28035c980bde01b9168e76442fe564dc82ae5b7)
[Proscream](mailto:proscream@naver.com) | multiple pages(asciinema to atoum) : Add Korean Translation (#3556) | 2019-11-26T19:49:10 | [3c656248966b](https://github.com/tldr-pages/tldr/commit/3c656248966bd2da299e8964d96ef6df09d8ed0f)

