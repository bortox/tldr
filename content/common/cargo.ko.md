---
author: ['Nicolas Kosinski', 'Proscream']
date: 1631346784
title: "cargo, TLDR Pages"
description: "cargo, Rust 패키지 관리프로그램."
categories: "common"
---
> Rust 프로젝트 및 해당 모듈 종속성(크레이트) 관리.

> 더 많은 정보: <https://crates.io/>.

- 크레이트 검색:

```bash
cargo search 검색할_문자열
```

- 크레이트 설치:

```bash
cargo install 크레이트_이름
```

- 설치된 크레이트 목록:

```bash
cargo install --list
```

- 현재 디렉토리에 새 이진 또는 라이브러리 Rust 프로젝트 생성:

```bash
cargo init --bin|lib
```

- 지정된 디렉토리에 새 이진 또는 라이브러리 Rust 프로젝트 생성:

```bash
cargo new 경로/디렉토리 --bin|lib
```

- 현재 디렉토리에 Rust 프로젝트 구축:

```bash
cargo build
```

- 특정 쓰레드 수를 사용하여 구축(기본값은 CPU 코어 수):

```bash
cargo build --jobs 작업
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Nicolas Kosinski](mailto:nicokosi@users.noreply.github.com) | cargo: use long options everywhere (#6502) | 2021-09-11T09:53:04 | [d3460ef8f103](https://github.com/tldr-pages/tldr/commit/d3460ef8f103a660f6f6765265b838b919342f1a)
[Proscream](mailto:proscream@naver.com) | Multiple pages(calibredb to case) : Add Korean Translation (#3582) | 2019-11-19T18:19:13 | [8181c0c27ef2](https://github.com/tldr-pages/tldr/commit/8181c0c27ef2d2f85fdb7c07a4a0f0e02bf5a4d3)

