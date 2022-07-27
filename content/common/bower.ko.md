---
author: ['Marco Bonelli', 'lch7167', 'Seth Falco', 'bl-ue']
date: 1648358715
title: "bower, TLDR Pages"
description: "bower, front-end 웹 개발에 최적화된 패키지 관리자. 패키지는 GitHub 사용자/reop 요약, Git의 엔드포인트, URL 혹은 등록된 패키지일 수 있습니다."
categories: "common"
---
> 더 많은 정보: <https://bower.io/>.

- bower.json에 나열된 프로젝트의 종속성 설치:

```bash
bower install
```

- bower_components 디렉토리에 하나 이상의 패키지 설치:

```bash
bower install 패키지 패키지
```

- bower_components 디렉토리에서 로컬로 패키지 제거:

```bash
bower uninstall 패키지 패키지
```

- 로컬 패키지 및 가능한 업데이트 나열:

```bash
bower list
```

- bower 명령에 대한 도움말 표시:

```bash
bower help 명령
```

- 패키지에 대한 bower.json 파일 생성:

```bash
bower init
```

- 특정 종속 버전을 설치하고, bower.json에 추가:

```bash
bower install 로컬명=패키지#버젼 --save
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Seth Falco](mailto:seth@falco.fun) | *: normalize colons (#7913) | 2022-03-27T07:25:15 | [27ff55fc2eea](https://github.com/tldr-pages/tldr/commit/27ff55fc2eea445eb5216c3b1d934960539fc024)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | multiple pages: normalize line endings from CRLF to LF | 2021-01-12T15:36:36 | [567dc4ce0663](https://github.com/tldr-pages/tldr/commit/567dc4ce0663231ea1b8b9533b327094eb82ba1f)
[Marco Bonelli](mailto:mebeim@users.noreply.github.com) | multiple pages: fix whitespace in Korean pages (#3603) | 2019-11-22T16:09:37 | [503e5f030cad](https://github.com/tldr-pages/tldr/commit/503e5f030cada020dd32b7d2bef431e2e8b5b2d8)
[lch7167](mailto:youngsj69@gmail.com) | multiple pages (boot to bup): add korean translation (#3587) | 2019-11-19T18:21:58 | [0f1332a5d517](https://github.com/tldr-pages/tldr/commit/0f1332a5d517f703c15b54fe39b4f23f77505e7f)

