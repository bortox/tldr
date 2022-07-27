---
author: ['Proscream']
date: 1574183629
title: "adb, TLDR Pages"
description: "adb, 안드로이드 디버그 브릿지: 안드로이드 에뮬레이터 객체 또는 연결된 안드로이드 장치와 통신."
categories: "common"
---
> 더 많은 정보: <https://developer.android.com/studio/command-line/adb>.

- adb 서버 프로세스가 실행되고 있고, 시작하는지 확인:

```bash
adb start-server
```

- adb 서버 프로세스 종료:

```bash
adb kill-server
```

- 대상 에뮬레이터/장치 객체에서 원격 쉘 시작:

```bash
adb shell
```

- 안드로이드 애플리케이션을 에뮬레이터/장치로 푸쉬:

```bash
adb install -r 경로/파일명.apk
```

- 대상 장치에서부터 파일/디렉토리를 복사:

```bash
adb pull 경로/장치_파일명_또는_디렉토리명 경로/로컬_목적지_디렉토리명
```

- 대상 장치로 파일/디렉토리 복사:

```bash
adb push 경로/로컬_파일명_또는_디렉토리명 경로/장치_목적지_directory
```

- 연결된 장치들의 목록 가져오기:

```bash
adb devices
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Proscream](mailto:proscream@naver.com) | multiple pages: add Korean Translation (#3549) | 2019-11-19T18:13:49 | [5dfacef13066](https://github.com/tldr-pages/tldr/commit/5dfacef1306610247597b34374d3b62d41bd2f6f)

