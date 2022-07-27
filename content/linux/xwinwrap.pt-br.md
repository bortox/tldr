---
author: ['Henrique Tsuyoshi Yara']
date: 1635196592
title: "xwinwrap, TLDR Pages"
description: "xwinwrap, Usa um reprodutor de vídeo ou um programa como plano de fundo."
categories: "linux"
---
> Mais informações: <https://github.com/ujjwal96/xwinwrap>.

- Reproduz um vídeo usando mpv:

```bash
xwinwrap -b -nf -ov -- mpv -wid wid --loop --no-audio --no-resume-playback --panscan=1.0 caminho/para/video.mp4
```

- Reproduz um vídeo em tela cheia usando mpv:

```bash
xwinwrap -b -nf -fs -ov -- mpv -wid wid --loop --no-audio --no-resume-playback --panscan=1.0 caminho/para/video.mp4
```

- Reproduz um vídeo usando mpv com 80% de opacidade:

```bash
xwinwrap -b -nf -ov -o 0.8 --- mpv -wid wid --loop --no-audio --no-resume-playback --panscan=1.0 caminho/para/video.mp4
```

- Reproduz um vídeo usando mpv em um segundo monitor 1600x900 com 1920 de distância do eixo X:

```bash
xwinwrap -g 1600x900+1920 -b -nf -ov -- mpv -wid wid --loop --no-audio --no-resume-playback --panscan=1.0 caminho/para/video.mkv
```
Lista de alterações feitas nesta documentação


Autor | Descrição | Formato de data ISO 8601 | Link para GitHub
------|-----|-----|-----
[Henrique Tsuyoshi Yara](mailto:henri.tsuyoshi@hotmail.com) | xwinwrap: add pt_BR translation (#7008) | 2021-10-25T23:16:32 | [41cebf70a008](https://github.com/tldr-pages/tldr/commit/41cebf70a008ed5744218f863755906f400cc3d6)

