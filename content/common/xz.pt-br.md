---
author: ['Marco Bonelli']
date: 1566793410
title: "xz, TLDR Pages"
description: "xz, Compactar ou descompactar arquivos com a extensão .xz ou .lzma."
categories: "common"
---
> Mais informações: <https://tukaani.org/xz/format.html>.

- Compactar um arquivo no formato xz:

```bash
xz arquivo
```

- Descompactar um arquivo no formato xz:

```bash
xz -d arquivo.xz
```

- Compactar um arquivo no formato lzma:

```bash
xz --format=lzma arquivo
```

- Descompactar um arquivo no formato lzma:

```bash
xz -d --format=lzma arquivo.lzma
```

- Descompactar um arquivo e escrever a saída no terminal:

```bash
xz -dc arquivo.xz
```

- Compactar um arquivo sem apagar o arquivo original:

```bash
xz -k arquivo
```

- Compactar um arquivo utilizando a compactação mais rápida:

```bash
xz -0 arquivo
```

- Compactar um arquivo utilizando a compactação mais eficiente:

```bash
xz -9 arquivo
```
Lista de alterações feitas nesta documentação


Autor | Descrição | Formato de data ISO 8601 | Link para GitHub
------|-----|-----|-----
[Marco Bonelli](mailto:marco@mebeim.net) | BCP47 to POSIX: rename Brazilian Portuguese folder. | 2019-08-26T06:23:30 | [54e1ade0a958](https://github.com/tldr-pages/tldr/commit/54e1ade0a958f3a08d9ed60f32b66188d0ecfb63)

