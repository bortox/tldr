---
author: ['bl-ue', 'Proscream', 'Marco Bonelli']
date: 1621541621
title: "alacritty"
description: "alacritty, 교차 플랫폼으로, GPU-가속 터미널 에뮬레이터."
categories: "common"
---
> 더 많은 정보: <https://github.com/alacritty/alacritty>.

- 새 Alacritty 창 열기:

```bash
alacritty
```

- 특정 디렉토리에서 실행:

```bash
alacritty --working-directory 경로/디렉토리명
```

- 새로운 Alacritty 창에서 명령어 실행:

```bash
alacritty -e 명령어
```

- 대체 구성파일 지정 (기본값 : `$XDG_CONFIG_HOME/alacritty/alacritty.yml`):

```bash
alacritty --config-file 경로/config.yml
```

- 재배치가 가능한 라이브 구성 설정으로 실행 (기본적으로 `alacritty.yml` 에서도 활성화 가능):

```bash
alacritty --live-config-reload --config-file 경로/config.yml
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | *: fix typos reported by Hunspell (#5848) Co-authored-by: marchersimon <50295997+marchersimon@users.noreply.github.com> Co-authored- [...] | 2021-05-20T22:13:41 | [8ebd171d6f00](https://github.com/tldr-pages/tldr/commit/8ebd171d6f001698709fefc02b1fd5cc9f3a99c4)
[Marco Bonelli](mailto:mebeim@users.noreply.github.com) | multiple pages: fix whitespace in Korean pages (#3603) | 2019-11-22T16:09:37 | [503e5f030cad](https://github.com/tldr-pages/tldr/commit/503e5f030cada020dd32b7d2bef431e2e8b5b2d8)
[Proscream](mailto:proscream@naver.com) | multiple pages: add Korean Translation (#3549) | 2019-11-19T18:13:49 | [5dfacef13066](https://github.com/tldr-pages/tldr/commit/5dfacef1306610247597b34374d3b62d41bd2f6f)

