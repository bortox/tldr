---
author: ['lch7167', 'bl-ue']
date: 1610462196
title: "copyq, TLDR Pages"
description: "copyq, 고급 기능을 갖춘 클립보드 매니저."
categories: "common"
---
> 더 많은 정보: <https://hluk.github.io/CopyQ/>.

- copyQ를 시작하여 클립보드 기록 저장:

```bash
copyq
```

- 현재 클립보드 내용 표시:

```bash
copyq clipboard
```

- 클립보드 기록에 원본 텍스트 삽입:

```bash
copyq add -- 텍스트1 텍스트2 텍스트3
```

- 이스케이프 시퀀스 ('\n', '\t')가 포함 된 텍스트를 클립보드 기록에 삽입:

```bash
copyq add 첫째 줄\n둘째 줄
```

- 클립보드 기록에서 처음 3개 항목의 내용을 출력:

```bash
copyq read 0 1 2
```

- 파일 내용을 클립보드에 복사:

```bash
copyq copy < 파일.txt
```

- JPEG 이미지를 클립보드에 복사:

```bash
copyq copy image/jpeg < 이미지.jpg
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | multiple pages: normalize line endings from CRLF to LF | 2021-01-12T15:36:36 | [567dc4ce0663](https://github.com/tldr-pages/tldr/commit/567dc4ce0663231ea1b8b9533b327094eb82ba1f)
[lch7167](mailto:youngsj69@gmail.com) | merge consul_to_cowsay (#3593) | 2019-11-22T16:21:20 | [3b31dfcc59bf](https://github.com/tldr-pages/tldr/commit/3b31dfcc59bf4f74075db7af37e193eebde977df)

