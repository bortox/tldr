---
author: ['Marco Bonelli', 'lch7167', 'bl-ue']
date: 1610731489
title: "avrdude, TLDR Pages"
description: "avrdude, Atmel AVR 마이크로 컨트롤러 프로그래밍을 위한 드라이버 프로그램."
categories: "common"
---
> 더 많은 정보: <https://www.nongnu.org/avrdude/>.

- AVR 마이크로 컨트롤러 읽기:

```bash
avrdude -p AVR_device -c programmer -U flash:r:file.hex:i
```

- AVR 마이크로 컨트롤러 쓰기:

```bash
avrdude -p AVR_device -c programmer -U flash:w:file.hex
```

- 사용 가능한 AVR 장치 목록:

```bash
avrdude -p \?
```

- 사용 가능한 AVR 프로그래머 목록:

```bash
avrdude -c \?
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | multiple pages: normalize "more information" labels (#5140) | 2021-01-15T18:24:49 | [c59f12aa9f55](https://github.com/tldr-pages/tldr/commit/c59f12aa9f55d85612ba22e4da86db293ff76977)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | multiple pages: normalize line endings from CRLF to LF | 2021-01-12T15:36:36 | [567dc4ce0663](https://github.com/tldr-pages/tldr/commit/567dc4ce0663231ea1b8b9533b327094eb82ba1f)
[Marco Bonelli](mailto:mebeim@users.noreply.github.com) | Add trailing newline to Korean pages (#3573) | 2019-11-15T16:59:10 | [07fab14d0e7b](https://github.com/tldr-pages/tldr/commit/07fab14d0e7b61291e76cd880594984bbc3e60e5)
[lch7167](mailto:youngsj69@gmail.com) | multiple pages: add korean translation (#3548) | 2019-11-12T22:17:52 | [a451d973e85d](https://github.com/tldr-pages/tldr/commit/a451d973e85daf798ecab99ce2a7937727a934da)

