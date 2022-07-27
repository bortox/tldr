---
author: ['Schneider', 'lch7167', 'bl-ue', 'marchersimon']
date: 1633112881
title: "blackfire, TLDR Pages"
description: "blackfire, PHP용 커맨드라인 프로파일링 도구."
categories: "common"
---
> 더 많은 정보: <https://blackfire.io>.

- Blackfire 클라이언트 초기화 및 구성:

```bash
blackfire config
```

- Blackfire agent 시작:

```bash
blackfire agent
```

- 특정 소켓에서 Blackfire agent 시작:

```bash
blackfire agent --socket="tcp://127.0.0.1:8307"
```

- 특정 프로그램에서 프로파일러 실행:

```bash
blackfire run 파일.php/의/php 경로
```

- 프로파일러 실행 및 샘플 10개 수집:

```bash
blackfire --samples=10 run 파일.php/의/php 경로
```

- 프로파일러 및 출력 결과를 JSON으로 실행:

```bash
blackfire --json run 파일.php/의/php 경로
```

- 프로파일러 파일을 Blackfire 웹 서비스에 업로드:

```bash
blackfire upload 파일/의/경로
```

- Blackfire 웹 서비스에서 프로필 상태 확인:

```bash
blackfire status
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: sync more information links in translations (#6537) | 2021-10-01T20:28:01 | [642dbf2e972e](https://github.com/tldr-pages/tldr/commit/642dbf2e972e388fab8c84ba3b4685fb862b6454)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | multiple pages: normalize "more information" labels (#5140) | 2021-01-15T18:24:49 | [c59f12aa9f55](https://github.com/tldr-pages/tldr/commit/c59f12aa9f55d85612ba22e4da86db293ff76977)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | multiple pages: normalize line endings from CRLF to LF | 2021-01-12T15:36:36 | [567dc4ce0663](https://github.com/tldr-pages/tldr/commit/567dc4ce0663231ea1b8b9533b327094eb82ba1f)
[Schneider](mailto:lucas.schneider@sap.com) | multiple ch pages: remove trailing whitespace | 2020-03-12T20:52:09 | [310c1e1f7607](https://github.com/tldr-pages/tldr/commit/310c1e1f7607c67e5651e4d3c118a43029639285)
[lch7167](mailto:youngsj69@gmail.com) | multiple pages: add korean translation (#3564) | 2019-11-18T02:50:21 | [894df52f44af](https://github.com/tldr-pages/tldr/commit/894df52f44af2b32579b1009d539956058766205)

