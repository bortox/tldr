---
author: ['lch7167', 'bl-ue', 'Marco Bonelli']
date: 1610731489
title: "balena"
description: "balena, 명령 줄에서 balenaCloud, openBalena 및 balena API와 상호 작용하십시오."
categories: "common"
---
> 더 많은 정보: <https://www.balena.io/docs/reference/cli/>.

- balenaCloud 계정에 로그인:

```bash
balena login
```

- BalencaCloud 또는 OpenBalena 애플리케이션 생성:

```bash
balena app create app_name
```

- 계정 내 모든 balenaCloud 또는 openBalena 애플리케이션 나열:

```bash
balena apps
```

- balenaCloud 또는 openBalena 계정과 관련된 모든 장치 나열:

```bash
balena devices
```

- BalenaOS 이미지를 로컬 드라이브에 플래시:

```bash
balena local flash path/to/balenaos.img --drive drive_location
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | multiple pages: normalize "more information" labels (#5140) | 2021-01-15T18:24:49 | [c59f12aa9f55](https://github.com/tldr-pages/tldr/commit/c59f12aa9f55d85612ba22e4da86db293ff76977)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | multiple pages: normalize line endings from CRLF to LF | 2021-01-12T15:36:36 | [567dc4ce0663](https://github.com/tldr-pages/tldr/commit/567dc4ce0663231ea1b8b9533b327094eb82ba1f)
[Marco Bonelli](mailto:mebeim@users.noreply.github.com) | Add trailing newline to Korean pages (#3573) | 2019-11-15T16:59:10 | [07fab14d0e7b](https://github.com/tldr-pages/tldr/commit/07fab14d0e7b61291e76cd880594984bbc3e60e5)
[lch7167](mailto:youngsj69@gmail.com) | multiple pages: add korean translation (#3548) | 2019-11-12T22:17:52 | [a451d973e85d](https://github.com/tldr-pages/tldr/commit/a451d973e85daf798ecab99ce2a7937727a934da)

