---
author: ['Schneider', 'lch7167', 'bl-ue', 'marchersimon']
date: 1633112881
title: "beanstalkd, TLDR Pages"
description: "beanstalkd, 단순하고 일반적인 work-queue 서버."
categories: "common"
---
> 더 많은 정보: <https://beanstalkd.github.io/>.

- beanstalkd를 시작하고, 11300 포트로 듣기:

```bash
beanstalkd
```

- 사용자가 지정한 포트 및 주소에서 beanstalkd 듣기 시작:

```bash
beanstalkd -l ip_address -p port_number
```

- work queue를 디스크에 저장하고 유지:

```bash
beanstalkd -b path/to/persistence_directory
```

- 500밀리초마다 지속성있는 디렉토리에 동기화:

```bash
beanstalkd -b path/to/persistence_directory -f 500
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: sync more information links in translations (#6537) | 2021-10-01T20:28:01 | [642dbf2e972e](https://github.com/tldr-pages/tldr/commit/642dbf2e972e388fab8c84ba3b4685fb862b6454)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | multiple pages: normalize "more information" labels (#5140) | 2021-01-15T18:24:49 | [c59f12aa9f55](https://github.com/tldr-pages/tldr/commit/c59f12aa9f55d85612ba22e4da86db293ff76977)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | multiple pages: normalize line endings from CRLF to LF | 2021-01-12T15:36:36 | [567dc4ce0663](https://github.com/tldr-pages/tldr/commit/567dc4ce0663231ea1b8b9533b327094eb82ba1f)
[Schneider](mailto:lucas.schneider@sap.com) | multiple ch pages: remove trailing whitespace | 2020-03-12T20:52:09 | [310c1e1f7607](https://github.com/tldr-pages/tldr/commit/310c1e1f7607c67e5651e4d3c118a43029639285)
[lch7167](mailto:youngsj69@gmail.com) | multiple pages: add korean translation (#3548) | 2019-11-12T22:17:52 | [a451d973e85d](https://github.com/tldr-pages/tldr/commit/a451d973e85daf798ecab99ce2a7937727a934da)

