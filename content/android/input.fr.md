---
author: ['Nicolas Hansse']
date: 1633372595
title: "input"
description: "input, Send event codes or touchscreen gestures to an Android device."
categories: "android"
---
> Envoie à un appareil Android des codes événements ou des gestes d'écran tactile.

> Cette commande peut être utilisé uniquement depuis `adb shell`.

> Plus d'informations : <https://developer.android.com/reference/android/view/KeyEvent.html#constants_1>.

- Envoie un code événement (un seul caractère) à un appareil Android :

```bash
input keyevent event_code
```

- Envoie du texte à un appareil Android (`%s` représentant les espaces) :

```bash
input text "text"
```

- Envoie un tapotement (tap) à un appareil Android :

```bash
input tap x_pos y_pos
```

- Envoie un mouvement de swipe à un appareil Android :

```bash
input swipe x_start y_start x_end y_end duration_in_ms
```

- Envoie un appui long à un appareil Android en utilisant un mouvement de swipe :

```bash
input swipe x_pos y_pos x_pos y_pos duration_in_ms
```
Liste des modifications apportées à cette documentation


Auteur | Description | Format de la date ISO 8601 | Lien vers GitHub
------|-----|-----|-----
[Nicolas Hansse](mailto:nico.hansse@gmail.com) | android/*: add French translation (#6716) | 2021-10-04T20:36:35 | [1a1fc29b50c3](https://github.com/tldr-pages/tldr/commit/1a1fc29b50c3a931756fb51d571ca61a43e70067)

