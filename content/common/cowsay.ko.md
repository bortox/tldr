---
author: ['lch7167', 'bl-ue', 'Nicolas Kosinski']
date: 1618337238
title: "cowsay"
description: "cowsay, 무언가를 말하거나 생각하는 ASCII 문자(기본적으로 cow)를 생성."
categories: "common"
---
> 더 많은 정보: <https://github.com/tnalpgge/rank-amateur-cowsay>.

- "Hello world"라고 말하는 ASCII cow 출력:

```bash
cowsay "Hello world"
```

- 풍선에 표준 입력의 텍스트 사용:

```bash
echo "Hello" | cowsay
```

- 사용 가능한 모든 문자 나열:

```bash
cowsay -l
```

- "Hello"라고 말하는 ASCII dragon 출력:

```bash
cowsay -f dragon "Hello"
```

- 돌로 된 생각하는 ASCII cow 출력:

```bash
cowthink -s "I'm just a cow, not a great thinker..."
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Nicolas Kosinski](mailto:nicokosi@yahoo.com) | cowsay: fix commands for zsh (#5742) | 2021-04-13T20:07:18 | [6c4068b01901](https://github.com/tldr-pages/tldr/commit/6c4068b01901f36d53686965b5c851d797309482)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | multiple pages: normalize line endings from CRLF to LF | 2021-01-12T15:36:36 | [567dc4ce0663](https://github.com/tldr-pages/tldr/commit/567dc4ce0663231ea1b8b9533b327094eb82ba1f)
[lch7167](mailto:youngsj69@gmail.com) | merge consul_to_cowsay (#3593) | 2019-11-22T16:21:20 | [3b31dfcc59bf](https://github.com/tldr-pages/tldr/commit/3b31dfcc59bf4f74075db7af37e193eebde977df)

