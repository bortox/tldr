---
author: ['cyqsimon']
date: 1639653526
title: "chcon"
description: "chcon, 파일 또는 파일/디렉토리의 SELinux 보안 내용 변경."
categories: "linux"
---
> 더 많은 정보: <https://www.gnu.org/software/coreutils/chcon>.

- 파일의 보안 내용 보기:

```bash
ls -lZ 경로/파일명
```

- 참조된 파일을 사용하여, 대상 파일의 보안 내용 변경:

```bash
chcon --reference=참조_파일명 대상_파일명
```

- 파일의 전체 SELinux 보안 내용 변경:

```bash
chcon 사용자:역할:타입:범위/레벨 파일명
```

- SELinux 보안 내용의 사용자 부분만 변경:

```bash
chcon -u 사용자 파일명
```

- SELinux 보안 내용의 역할 부분만 변경:

```bash
chcon -r 역할 파일명
```

- SELinux 보안 컨텍스트의 타입 부분만 변경:

```bash
chcon -t 타입 파일명
```

- SELinux 보안 컨텍스트의 범위/레벨 부분만 변경:

```bash
chcon -l 범위/레벨 파일명
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[cyqsimon](mailto:28627918+cyqsimon@users.noreply.github.com) | chcon: move from common to linux platform (#7544) | 2021-12-16T12:18:46 | [df0117359b09](https://github.com/tldr-pages/tldr/commit/df0117359b099af835e8d16c88ff631b7e71f804)

