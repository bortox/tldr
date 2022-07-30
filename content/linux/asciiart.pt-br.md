---
author: ['Henrique Tsuyoshi Yara']
date: 1633877152
title: "asciiart"
description: "asciiart, Converte imagens para ASCII."
categories: "linux"
---
> Mais informações: <https://github.com/nodanaonlyzuul/asciiart>.

- Lê uma imagem de um arquivo e imprime em ASCII:

```bash
asciiart caminho/para/imagem.jpg
```

- Lê uma imagem de uma URL e imprime em ASCII:

```bash
asciiart www.exemplo.com/imagem.jpg
```

- Escolha a largura da saída (o padrão é 100):

```bash
asciiart --width 50 caminho/para/imagem.jpg
```

- Imprimir com cor:

```bash
asciiart --color caminho/para/imagem.jpg
```

- Escolha o formato de saída (o padrão é text):

```bash
asciiart --format text|html caminho/para/imagem.jpg
```

- Inverter o mapeamento dos caracteres:

```bash
asciiart --invert-chars caminho/para/imagem.jpg
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Henrique Tsuyoshi Yara](mailto:henri.tsuyoshi@hotmail.com) | asciiart: add pt_BR translation (#6917) | 2021-10-10T16:45:52 | [0b9b6f44966a](https://github.com/tldr-pages/tldr/commit/0b9b6f44966aa2ecd9f9839b073dbdbb671a5dc1)

