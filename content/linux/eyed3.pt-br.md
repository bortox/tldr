---
author: ['pixel', 'bl-ue']
date: 1632941775
title: "eyeD3"
description: "eyeD3, Lê e manipula os metadados de arquivos MP3."
categories: "linux"
---
> Mais informações: <https://eyed3.readthedocs.io>.

- Visualizar as informações de um arquivo MP3:

```bash
eyeD3 arquivo.mp3
```

- Definir o título de um arquivo MP3:

```bash
eyeD3 --title "titulo" arquivo.mp3
```

- Definir o álbum de todos os arquivos MP3 de um diretório:

```bash
eyeD3 --album "nome_do_album" *.mp3
```

- Definir a capa do álbum para um arquivo MP3:

```bash
eyeD3 --add-image capa.jpeg:FRONT_COVER: arquivo.mp3
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[pixel](mailto:chrissx@chrissx.de) | *: normalize readthedocs.io more information links (#6593) | 2021-09-29T20:56:15 | [d22ca9676f6c](https://github.com/tldr-pages/tldr/commit/d22ca9676f6c02b19e6e1728f5ea777e7985c9d0)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | eyeD3: rename to eyed3 (#5381) | 2021-03-09T14:28:36 | [a0fd30d78402](https://github.com/tldr-pages/tldr/commit/a0fd30d78402e5e5f0243af7784748695c33152f)

