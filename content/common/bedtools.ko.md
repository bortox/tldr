---
author: ['Schneider', 'Marco Bonelli', 'lch7167', 'pixel', 'Lucas Gabriel Schneider', 'bl-ue']
date: 1632941775
title: "bedtools, TLDR Pages"
description: "bedtools, 유전자 분석 작업을 위한 도구의 swiss-army knife. BAM, BED, GFF/GTF, VCF 형식으로 데이터를 교차, 그룹화, 변환 및 카운트하는 데 사용."
categories: "common"
---
> 더 많은 정보: <https://bedtools.readthedocs.io>.

- sequence의 strand를 기준으로 두개의 파일을 교차하고 결과를 `path/to/output_file`의 경로에 저장:

```bash
bedtools intersect -a path/to/file_1 -b path/to/file_2 -s > path/to/output_file
```

- 외부 조인이 왼쪽인 두개의 파일을 교차, 예시. `file_1`에서 각 기능을 보고하고 `file_2`와 겹치지 않으면 NULL:

```bash
bedtools intersect -a path/to/file_1 -b path/to/file_2 -lof > path/to/output_file
```

- 더 효율적인 알고리즘을 사용하여 두개의 사전 정렬된 파일을 교차:

```bash
bedtools intersect -a path/to/file_1 -b path/to/file_2 -sorted > path/to/output_file
```

- 첫 3열과 5열을 기준으로 `path/to/file`을 그룹화하여 6열을 요약:

```bash
bedtools groupby -i path/to/file -c 1-3,5 -g 6 -o sum
```

- bam-formated 파일을 bed-formated 파일로 변환:

```bash
bedtools bamtobed -i path/to/file.bam > path/to/file.bed
```

- `file_2.bed`와 가장 가까운 `file_1.bed`에서의 모든 기능을 찾고,그들의 거리와 추가 열을 기록 (입력 파일 정렬 필요):

```bash
bedtools closest -a path/to/file_1.bed -b path/to/file_2.bed -d
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[pixel](mailto:chrissx@chrissx.de) | *: normalize readthedocs.io more information links (#6593) | 2021-09-29T20:56:15 | [d22ca9676f6c](https://github.com/tldr-pages/tldr/commit/d22ca9676f6c02b19e6e1728f5ea777e7985c9d0)
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | multiple pages: format technical tokens (#5119) Co-authored-by: bl-ue <54780737+bl-ue@users.noreply.github.com> Co-authored-by: [...] | 2021-01-31T18:05:18 | [a5fe31bc47ae](https://github.com/tldr-pages/tldr/commit/a5fe31bc47aece3efa5e66b52b3cf384f27d5d72)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | multiple pages: normalize "more information" labels (#5140) | 2021-01-15T18:24:49 | [c59f12aa9f55](https://github.com/tldr-pages/tldr/commit/c59f12aa9f55d85612ba22e4da86db293ff76977)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | multiple pages: normalize line endings from CRLF to LF | 2021-01-12T15:36:36 | [567dc4ce0663](https://github.com/tldr-pages/tldr/commit/567dc4ce0663231ea1b8b9533b327094eb82ba1f)
[Schneider](mailto:lucas.schneider@sap.com) | multiple ch pages: remove trailing whitespace | 2020-03-12T20:52:09 | [310c1e1f7607](https://github.com/tldr-pages/tldr/commit/310c1e1f7607c67e5651e4d3c118a43029639285)
[Marco Bonelli](mailto:mebeim@users.noreply.github.com) | Add trailing newline to Korean pages (#3573) | 2019-11-15T16:59:10 | [07fab14d0e7b](https://github.com/tldr-pages/tldr/commit/07fab14d0e7b61291e76cd880594984bbc3e60e5)
[lch7167](mailto:youngsj69@gmail.com) | multiple pages: add korean translation (#3548) | 2019-11-12T22:17:52 | [a451d973e85d](https://github.com/tldr-pages/tldr/commit/a451d973e85daf798ecab99ce2a7937727a934da)

