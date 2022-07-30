---
author: ['Andreia Bohner']
date: 1658135504
title: "base64"
description: "base64, Codifica e decodifica usando a representação Base64."
categories: "osx"
---
> Mais informações: <https://www.unix.com/man-page/osx/1/base64/>.

- Codificar um arquivo:

```bash
base64 --input=arquivo
```

- Decodificar um arquivo:

```bash
base64 --decode --input=arquivo_base64
```

- Codificar de stdin:

```bash
echo -n "texto" | base64
```

- Decodificar de stdin:

```bash
echo -n texto_base64 | base64 --decode
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Andreia Bohner](mailto:andreiabohner@gmail.com) | base64: add pt_BR translation | 2022-07-18T11:11:44 | [1b798b0e380e](https://github.com/tldr-pages/tldr/commit/1b798b0e380e6f6074bfb4862f4c99244dc5ce87)

