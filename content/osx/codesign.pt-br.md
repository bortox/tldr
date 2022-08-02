---
author: ['Andréia Bohner']
date: 1659378325
title: "codesign"
description: "codesign, Cria e manipula assinaturas de código para macOS."
categories: "osx"
---
> Mais informações: <https://www.unix.com/man-page/osx/1/codesign/>.

- Assina um aplicativo com um certificado:

```bash
codesign --sign "Nome da Minha Empresa" caminho/para/App.app
```

- Verifica o certificado de um aplicativo:

```bash
codesign --verify caminho/para/App.app
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Andréia Bohner](mailto:andreiabohner@gmail.com) | osx/*: add pt_BR translations (#8269) | 2022-08-01T20:25:25 | [97b386939aa5](https://github.com/tldr-pages/tldr/commit/97b386939aa505be651794a55d3bea20b4f14ab2)

