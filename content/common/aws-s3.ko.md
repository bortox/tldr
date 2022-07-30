---
author: ['Schneider', 'Marco Bonelli', 'lch7167', 'bl-ue', 'lincc']
date: 1636372515
title: "aws s3"
description: "aws s3, AWS S3용 CLI - 웹 서비스 인터페이스를 통해 스토리지를 제공합니다."
categories: "common"
---
> 더 많은 정보: <https://awscli.amazonaws.com/v2/documentation/api/latest/reference/s3/index.html>.

- 버킷 안의 파일 보기:

```bash
aws s3 ls bucket_name
```

- 로컬에서 버킷으로 파일 및 디렉토리 동기화:

```bash
aws s3 sync path/to/files s3://bucket_name
```

- 버킷에서 로컬로 파일 및 디렉토리 동기화:

```bash
aws s3 sync s3://bucket_name path/to/target
```

- 제외 된 파일 및 디렉토리 동기화:

```bash
aws s3 sync path/to/files s3://bucket_name --exclude path/to/file --exclude path/to/directory/*
```

- 버킷에서 파일 제거:

```bash
aws s3 rm s3://bucket/path/to/file
```

- 변경 사항만 미리보기:

```bash
aws s3 any_command --dryrun
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[lincc](mailto:46962923+blueskyson@users.noreply.github.com) | *: sync alias pages in translations (#6846) | 2021-11-08T12:55:15 | [d51f4893e973](https://github.com/tldr-pages/tldr/commit/d51f4893e973508f79168db1220c0556c9f88743)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | multiple pages: normalize "more information" labels (#5140) | 2021-01-15T18:24:49 | [c59f12aa9f55](https://github.com/tldr-pages/tldr/commit/c59f12aa9f55d85612ba22e4da86db293ff76977)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | multiple pages: normalize line endings from CRLF to LF | 2021-01-12T15:36:36 | [567dc4ce0663](https://github.com/tldr-pages/tldr/commit/567dc4ce0663231ea1b8b9533b327094eb82ba1f)
[Schneider](mailto:lucas.schneider@sap.com) | multiple ch pages: remove trailing whitespace | 2020-03-12T20:52:09 | [310c1e1f7607](https://github.com/tldr-pages/tldr/commit/310c1e1f7607c67e5651e4d3c118a43029639285)
[Marco Bonelli](mailto:mebeim@users.noreply.github.com) | Add trailing newline to Korean pages (#3573) | 2019-11-15T16:59:10 | [07fab14d0e7b](https://github.com/tldr-pages/tldr/commit/07fab14d0e7b61291e76cd880594984bbc3e60e5)
[lch7167](mailto:youngsj69@gmail.com) | multiple pages: add korean translation (#3548) | 2019-11-12T22:17:52 | [a451d973e85d](https://github.com/tldr-pages/tldr/commit/a451d973e85daf798ecab99ce2a7937727a934da)

