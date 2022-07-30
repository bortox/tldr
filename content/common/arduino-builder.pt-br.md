---
author: ['Luis Felipe Santos do Nascimento']
date: 1620319123
title: "arduino-builder"
description: "arduino-builder, Uma ferramenta de linha de comando para compilar sketches do arduino."
categories: "common"
---
> AVIDO DE OBSOLESCÊNCIA: Esta ferramenta está sendo descontinuada e substituida pelo `arduino`.

> Mais informações: <https://github.com/arduino/arduino-builder>.

- Compilar um sketch:

```bash
arduino-builder -compile caminho/para/sketch.ino
```

- Definir o nível de debug (1 a 10, o padrão é 5):

```bash
arduino-builder -debug-level nivel
```

- Definir um diretório de compilação customizado:

```bash
arduino-builder -build-path caminho/para/diretorio
```

- Usar um arquivo com as opções de compilação, em vez de especificar `--hardware`, `--tools`, etc. manualmente toda hora:

```bash
arduino-builder -build-options-file caminho/para/build.options.json
```

- Habilitar o modo verboso:

```bash
arduino-builder -verbose true
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Luis Felipe Santos do Nascimento](mailto:luisfelipesdn12@gmail.com) | [, arduino-builder, arduino, bash, clear: add pt-BR translation (#5874) | 2021-05-06T18:38:43 | [0a5e31e1c7f3](https://github.com/tldr-pages/tldr/commit/0a5e31e1c7f3a48ec206ca07bb1ffb1cd0fb39c0)

