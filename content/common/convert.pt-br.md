---
author: ['Rui Alves', 'bl-ue']
date: 1621541621
title: "convert"
description: "convert, Ferramenta de conversão de imagens da ImageMagick."
categories: "common"
---
> Mais informações: <https://imagemagick.org/script/convert.php>.

- Converter uma imagem do formato JPG para o formato PNG:

```bash
convert imagem.jpg imagem.png
```

- Escalar uma imagem para 50% do seu tamanho original:

```bash
convert imagem.png -resize 50% nova_imagem.png
```

- Escalar uma imagem, mantendo as suas proporções originais, para uma dimensão máxima de 640x480:

```bash
convert imagem.png -resize 640x480 nova_imagem.png
```

- Juntar várias imagens horizontalmente:

```bash
convert imagem1.png imagem2.png imagem3.png +append nova_imagem.png
```

- Criar um GIF a partir de uma série de imagens, com um intervalo de 100ms entre elas:

```bash
convert imagem1.png imagem2.png imagem3.png -delay 100 nova_imagem.gif
```

- Criar uma nova imagem de tamanho 800x600 com apenas um fundo sólido vermelho:

```bash
convert -size 800x600 "xc:#ff0000" imagem.png
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | *: fix typos reported by Hunspell (#5848) Co-authored-by: marchersimon <50295997+marchersimon@users.noreply.github.com> Co-authored- [...] | 2021-05-20T22:13:41 | [8ebd171d6f00](https://github.com/tldr-pages/tldr/commit/8ebd171d6f001698709fefc02b1fd5cc9f3a99c4)
[Rui Alves](mailto:up201606746@fe.up.pt) | convert: add pt_BR translation (#3385) | 2019-10-13T15:56:18 | [7e66b567f177](https://github.com/tldr-pages/tldr/commit/7e66b567f177f8953e9bf907f8232eafd7033c6f)

