---
author: ['Felipe-noob']
date: 1632139097
title: "img2pdf, TLDR Pages"
description: "img2pdf, Ferramenta de conversão sem perdas de imagens para PDF."
categories: "common"
---
> Mais informações: <https://gitlab.mister-muffin.de/josch/img2pdf>.

- Converter múltiplas imagens para um único PDF, cada imagem sendo uma página:

```bash
img2pdf caminho/da/imagem1.jpg caminho/da/imagem2.jpg --output caminho/do/arquivo.pdf
```

- Converter para PDF apenas o primeiro quadro de uma imagem com múltiplos quadros:

```bash
img2pdf caminho/do/arquivo.gif --first-frame-only --output caminho/do/arquivo.pdf
```

- Auto-orientar a imagem, usar uma página A4 em modo paisagem e uma borda de 2cm horizontalmente e 5.1cm verticalmente:

```bash
img2pdf caminho/do/arquivo.jpg --auto-orient --pagesize A4^T --border 2cm:5.1cm --output caminho/do/arquivo.pdf
```

- Encolher apenas imagens maiores para um retângulo de 10cm por 15cm dentro de uma página de 30x20cm:

```bash
img2pdf caminho/do/arquivo.tiff --pagesize 30cmx20cm --imgsize 10cmx15cm --fit shrink --output caminho/do/arquivo.pdf
```

- Converter uma imagem para PDF e especificar os metadados do arquivo resultante:

```bash
img2pdf caminho/do/arquivo.png --title título --author autor --creationdate 1970-01-31 --keywords palavra_chave1 palavra_chave2 --subject assunto --output caminho/do/arquivo.pdf
```
Lista de alterações feitas nesta documentação


Autor | Descrição | Formato de data ISO 8601 | Link para GitHub
------|-----|-----|-----
[Felipe-noob](mailto:80780954+Felipe-noob@users.noreply.github.com) | img2pdf: add pt_BR translation (#6546) | 2021-09-20T13:58:17 | [b0a03e46c5d2](https://github.com/tldr-pages/tldr/commit/b0a03e46c5d2b1119edcf0a5772908c062032a57)

