---
author: ['lch7167', 'bl-ue']
date: 1610462196
title: "convmv"
description: "convmv, 한 인코딩에서 다른 인코딩으로 파일 이름(파일 내용 X)을 변환."
categories: "common"
---
> 더 많은 정보: <https://www.j3e.de/linux/convmv/man/>.

- 파일 이름 인코딩 변환 테스트(파일 이름을 실제로 변경하지 마십시오):

```bash
convmv -f 인코딩_에서 -t 인코딩_으로 입력_파일
```

- 파일 이름 인코딩을 변환하고 파일 이름을 새 인코딩으로 변환:

```bash
convmv -f 인코딩_에서 -t 인코딩_으로 --notest 입력_파일
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | multiple pages: normalize line endings from CRLF to LF | 2021-01-12T15:36:36 | [567dc4ce0663](https://github.com/tldr-pages/tldr/commit/567dc4ce0663231ea1b8b9533b327094eb82ba1f)
[lch7167](mailto:youngsj69@gmail.com) | merge consul_to_cowsay (#3593) | 2019-11-22T16:21:20 | [3b31dfcc59bf](https://github.com/tldr-pages/tldr/commit/3b31dfcc59bf4f74075db7af37e193eebde977df)

