---
author: ['bl-ue', 'Proscream']
date: 1617493464
title: "asciinema, TLDR Pages"
description: "asciinema, 터미널 세션을 녹음하고 재생하며 선택적으로 asciinema.org에서 공유합니다."
categories: "common"
---
> 더 많은 정보: <https://asciinema.org/>.

- `asciinema` 로컬 설치와 with an asciinema.org 계정을 연결하기:

```bash
asciinema auth
```

- 새로운 녹음을 작성 (한 번 완료되면 사용자는 업로드하거나 로컬로 저장하라는 메시지가 표시됩니다):

```bash
asciinema rec
```

- 새 녹음을 만들고 로컬 파일에 저장:

```bash
asciinema rec 경로/파일명.cast
```

- 로컬 파일에서 녹음한 터미널을 재생:

```bash
asciinema play 경로/파일명.cast
```

- asciinema.org에서 호스트된 터미널 녹음을 재생:

```bash
asciinema play https://asciinema.org/a/cast_id
```

- 새로운 녹음을 만들어 유휴 시간을 최대 2.5초로 제한:

```bash
asciinema rec -i 2.5
```

- 로컬 저장 기록의 전체 출력을 인쇄:

```bash
asciinema cat 경로/파일명.cast
```

- 로컬로 저장된 터미널 세션을 asciinema.org에 업로드하기:

```bash
asciinema upload 경로/파일명.cast
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | *: trim multiple spaces, fix line endings | 2021-04-04T01:44:24 | [04dd546e2de7](https://github.com/tldr-pages/tldr/commit/04dd546e2de7f59f40a867acca6f46b0dc8ea9b4)
[Proscream](mailto:proscream@naver.com) | multiple pages(asciinema to atoum) : Add Korean Translation (#3556) | 2019-11-26T19:49:10 | [3c656248966b](https://github.com/tldr-pages/tldr/commit/3c656248966bd2da299e8964d96ef6df09d8ed0f)

