---
author: ['Andréia Bohner']
date: 1659378325
title: "carthage"
description: "carthage, Ferramenta de gerenciamento de dependências para aplicativos Cocoa."
categories: "osx"
---
> Mais informações: <https://github.com/Carthage/Carthage>.

- Baixa a versão mais recente de todas as dependências mencionadas no Cartfile e realiza o build delas:

```bash
carthage update
```

- Atualiza as dependências, e faz build apenas para o iOS:

```bash
carthage update --platform ios
```

- Atualiza as dependências, sem realizar build de nenhuma delas:

```bash
carthage update --no-build
```

- Faz o download e rebuild da versão atual das dependências (sem atualizá-las):

```bash
carthage bootstrap
```

- Faz o rebuild de uma dependência específica:

```bash
carthage build dependência
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Andréia Bohner](mailto:andreiabohner@gmail.com) | osx/*: add pt_BR translations (#8269) | 2022-08-01T20:25:25 | [97b386939aa5](https://github.com/tldr-pages/tldr/commit/97b386939aa505be651794a55d3bea20b4f14ab2)

