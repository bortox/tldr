---
author: ['Marco Bonelli', 'marchersimon']
date: 1633112881
title: "7za, TLDR Pages"
description: "7za, Um compactador de arquivos com alta taxa de compressão."
categories: "common"
---
> Versão compacta do `7z`, com suporte para menos tipos de arquivamento/compressão.

> Mais informações: <https://www.7-zip.org>.

- Compactar um arquivo ou diretório:

```bash
7za a arquivo_compactado.7z caminho/arquivo_ou_diretório
```

- Descompactar um arquivo mantendo a estrutura de diretórios original:

```bash
7za x arquivo_compactado.7z
```

- Compactar utilizando um tipo específico de arquivamento/compressão:

```bash
7za a -tzip|gzip|bzip2|tar arquivo_compactado.7z caminho/arquivo_ou_diretório
```

- Exibir os tipos de arquivamento/compressão disponíveis:

```bash
7za i
```

- Exibir o conteúdo de um arquivo:

```bash
7za l arquivo.7z
```
Lista de alterações feitas nesta documentação


Autor | Descrição | Formato de data ISO 8601 | Link para GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: sync more information links in translations (#6537) | 2021-10-01T20:28:01 | [642dbf2e972e](https://github.com/tldr-pages/tldr/commit/642dbf2e972e388fab8c84ba3b4685fb862b6454)
[Marco Bonelli](mailto:marco@mebeim.net) | BCP47 to POSIX: rename Brazilian Portuguese folder. | 2019-08-26T06:23:30 | [54e1ade0a958](https://github.com/tldr-pages/tldr/commit/54e1ade0a958f3a08d9ed60f32b66188d0ecfb63)

