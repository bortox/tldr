---
author: ['Marco Bonelli', 'lch7167', 'Kevin Lee', 'bl-ue']
date: 1633376057
title: "babel, TLDR Pages"
description: "babel, 코드를 JavaScript ES6/ES7 문법에서 ES5 문법으로 변환하는 변환기입니다."
categories: "common"
---
> 더 많은 정보: <https://babeljs.io/>.

- 지정된 입력 파일을 변환하고 `stdout'으로 출력:

```bash
babel path/to/file
```

- 지정된 입력 파일을 변환하고 특정 파일로 출력:

```bash
babel path/to/input_file --out-file path/to/output_file
```

- 입력 파일이 변경될 때마다 변환:

```bash
babel path/to/input_file --watch
```

- 파일의 전체 디렉토리를 변환:

```bash
babel path/to/input_directory
```

- 디렉토리에서 지정된 쉼표로 구분된 파일 무시:

```bash
babel path/to/input_directory --ignore ignored_files
```

- 축소된 JavaScript로 변환 및 출력:

```bash
babel path/to/input_file --minified
```

- 출력 형식에 대한 사전 설정 세트를 선택:

```bash
babel path/to/input_file --presets presets
```

- 사용 가능한 모든 옵션 출력:

```bash
babel --help
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Kevin Lee](mailto:kylee1112@hotmail.com) | babel: fix Korean translation (#6791) | 2021-10-04T21:34:17 | [20dd08635ddf](https://github.com/tldr-pages/tldr/commit/20dd08635ddfb8df6dacd02e9dacb487deb055ad)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | multiple pages: normalize "more information" labels (#5140) | 2021-01-15T18:24:49 | [c59f12aa9f55](https://github.com/tldr-pages/tldr/commit/c59f12aa9f55d85612ba22e4da86db293ff76977)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | multiple pages: normalize line endings from CRLF to LF | 2021-01-12T15:36:36 | [567dc4ce0663](https://github.com/tldr-pages/tldr/commit/567dc4ce0663231ea1b8b9533b327094eb82ba1f)
[Marco Bonelli](mailto:mebeim@users.noreply.github.com) | Add trailing newline to Korean pages (#3573) | 2019-11-15T16:59:10 | [07fab14d0e7b](https://github.com/tldr-pages/tldr/commit/07fab14d0e7b61291e76cd880594984bbc3e60e5)
[lch7167](mailto:youngsj69@gmail.com) | multiple pages: add korean translation (#3548) | 2019-11-12T22:17:52 | [a451d973e85d](https://github.com/tldr-pages/tldr/commit/a451d973e85daf798ecab99ce2a7937727a934da)

