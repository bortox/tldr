---
author: ['bl-ue', 'Proscream', 'Guido Lena Cota']
date: 1615233571
title: "dexter"
description: "dexter, OpenId Connect를 사용하여 Kubectl 사용자를 인증하는 도구."
categories: "common"
---
> 더 많은 정보: <https://github.com/gini/dexter>.

- Google OIDC로 사용자 생성 및 인증:

```bash
dexter auth -i 클라이언트_아이디 -s 클라이언트_secret
```

- 기본 kube 구성파일 위치 재정의:

```bash
dexter auth -i 클라이언트_아이디 -s 클라이언트_secret --kube-config 예시/구성파일
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | Korean pages: fix (valid) tldr-lint errors (#5376) | 2021-03-08T20:59:31 | [4061936c0ca2](https://github.com/tldr-pages/tldr/commit/4061936c0ca2344cc9beb92218dbf02e583fee83)
[Guido Lena Cota](mailto:guido.lenacota@gmail.com) | multiple pages: Use snake_case in token syntax (#4788) | 2020-11-01T14:40:05 | [0bb9c353a717](https://github.com/tldr-pages/tldr/commit/0bb9c353a717513283f8cda8493e5370ca47219a)
[Proscream](mailto:proscream@naver.com) | dexter : Add Korean Translation (#3671) | 2019-12-21T00:09:37 | [b7d93098854f](https://github.com/tldr-pages/tldr/commit/b7d93098854fae8b6d1f61de441dff683bc33a76)

