---
author: ['Schneider', 'Proscream']
date: 1584042729
title: "dotnet, TLDR Pages"
description: "dotnet, .NET Core를 위한 크로스 플랫폼 .NET 명령어 도구."
categories: "common"
---
> 더 많은 정보: <https://docs.microsoft.com/dotnet/core/tools>.

- 새 .NET 프로젝트 초기화하기:

```bash
dotnet new 짧은_템플릿_이름
```

- nuget 패키지들 복구하기:

```bash
dotnet restore
```

- 현재 디렉토리에서 .NET 프로젝트를 빌드하고 실행하기:

```bash
dotnet run
```

- 패키지화 된 dotnet 어플리케이션을 실행하기(런타임만 필요하며, 나머지 명령어들은 .NET Core SDK 설치가 필요):

```bash
dotnet 경로/어플리케이션.dll
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Schneider](mailto:lucas.schneider@sap.com) | multiple ch pages: remove trailing whitespace | 2020-03-12T20:52:09 | [310c1e1f7607](https://github.com/tldr-pages/tldr/commit/310c1e1f7607c67e5651e4d3c118a43029639285)
[Proscream](mailto:proscream@naver.com) | dotnet : Add Korean Translation (#3878) | 2020-02-26T21:40:36 | [28bc9817807a](https://github.com/tldr-pages/tldr/commit/28bc9817807a70bbade2ba7edb747d87db2c95a4)

