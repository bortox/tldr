---
author: ['Choi Young-jin']
date: 1649632199
title: "aapt"
description: "aapt, Android Asset Packaging Tool."
categories: "common"
---
> 안드로이드 앱의 소스를 컴파일하고 패키징합니다.

> 더 많은 정보: <https://elinux.org/Android_aapt>.

- APK 아카이브에 포함된 파일 나열:

```bash
aapt list 경로/app.apk
```

- 앱의 메타데이타 출력 (버전, 권한, 등등...):

```bash
aapt dump badging 경로/app.apk
```

- 지정된 디렉토리에 새 APK 아카이브 생성:

```bash
aapt package -F 경로/app.apk 디렉토리/의/경로
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Choi Young-jin](mailto:amateur.toss@gmail.com) | 2to3, 7za, 7zr, [, [[, aapt: add Korean translate (#7970) | 2022-04-11T01:09:59 | [14a5e6b02006](https://github.com/tldr-pages/tldr/commit/14a5e6b02006ec880b4133a9faac5afdf00ff62e)

