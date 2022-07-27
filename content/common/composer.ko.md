---
author: ['JJByun', 'Seth Falco', 'bl-ue']
date: 1648358715
title: "composer, TLDR Pages"
description: "composer, PHP 프로젝트의 의존성(dependency)을 기반으로 한 매니저 패키지."
categories: "common"
---
> 더 많은 정보: <https://getcomposer.org/>.

- 프로젝트의 의존성(dependency)으로 패키지를 추가합니다, 다음에 추가합니다 `composer.json`:

```bash
composer require 사용자/패키지명
```

- 프로젝트의 `composer.json` 안에 모든 의존성(dependency)를 설치합니다:

```bash
composer install
```

- 프로젝트의 패키지를 제거하며 `composer.json` 안의 모든 의존성(dependency)를 제거합니다:

```bash
composer remove 사용자/패키지명
```

- 프로젝트의 `composer.json` 파일의 모든 의존성(dependency)를 업데이트 합니다:

```bash
composer update
```

- composer를 최신 버전으로 업데이트 합니다:

```bash
composer self-update
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Seth Falco](mailto:seth@falco.fun) | *: normalize colons (#7913) | 2022-03-27T07:25:15 | [27ff55fc2eea](https://github.com/tldr-pages/tldr/commit/27ff55fc2eea445eb5216c3b1d934960539fc024)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | Korean pages: fix (valid) tldr-lint errors (#5376) | 2021-03-08T20:59:31 | [4061936c0ca2](https://github.com/tldr-pages/tldr/commit/4061936c0ca2344cc9beb92218dbf02e583fee83)
[JJByun](mailto:jd0909@naver.com) | mutiple pages(complete to consul-kv) : Add Korean Translation (#3596) | 2019-11-22T16:08:47 | [21c755e52ade](https://github.com/tldr-pages/tldr/commit/21c755e52ade9452392011d02ec34fbb1dfa4db5)

