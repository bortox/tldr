---
author: ['Rafael Julio']
date: 1634750179
title: "input"
description: "input, Envia códigos de evento ou gestos de toque para um dispositivo Android."
categories: "android"
---
> Esse comando só pode ser usado através de `adb shell`.

> Mais informações: <https://developer.android.com/reference/android/view/KeyEvent.html#constants_1>.

- Envia um código de evento de um caractere para um dispositivo Android:

```bash
input keyevent codigo_de_evento
```

- Envia texto para um dispositivo Android (`%s` representa espaços):

```bash
input text "texto"
```

- Envia um único toque para um dispositivo Android:

```bash
input tap x_pos y_pos
```

- Envia um gesto de deslizar para um dispositivo Android:

```bash
input swipe x_inicio y_inicio x_fim y_fim duração_em_ms
```

- Envia um pressionamento longo usando gesto de deslizar para um dispositivo Android:

```bash
input swipe x_pos y_pos x_pos y_pos duração_em_ms
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Rafael Julio](mailto:development@rafifos.dev) | dalvikvm, dumpsys, getprop, input: add pt_BR translation (#7063) | 2021-10-20T19:16:19 | [c3b2c27dd9b9](https://github.com/tldr-pages/tldr/commit/c3b2c27dd9b964b85b4f1074a62a6e725ee0f70a)

