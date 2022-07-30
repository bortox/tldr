---
author: ['Eduardo Lemos Júnior', 'marchersimon']
date: 1633112881
title: "zip"
description: "zip, Ferramenta de compressão de arquivos em arquivos zip."
categories: "common"
---
> Mais informações: <https://manned.org/zip>.

- Compactando arquivos em um arquivo zip:

```bash
zip output.zip arquivo1 arquivo2 arquivo3
```

- Compactando todos os arquivos de um diretório:

```bash
zip output.zip caminho/do/diretorio/*
```

- Adicionando arquivos a um arquivo zip existente:

```bash
zip arquivo_existente.zip caminho/do/diretorio
```

- Compactando todos os arquivos de um diretório mantendo estruturas de diretórios:

```bash
zip -r output.zip caminho/do/diretorio
```

- Compactando arquivos de um diretório excluindo arquivos específicos:

```bash
zip -r output.zip caminho/do/diretorio -x caminho/a/ser/excluido
```

- Compactando arquivos definindo o nível de compressão [9]:

```bash
zip -r -9 output.zip caminho/do/diretorio
```

- Deletando arquivos de um arquivo zip:

```bash
zip -d output.zip "foo/*.ext"
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: sync more information links in translations (#6537) | 2021-10-01T20:28:01 | [642dbf2e972e](https://github.com/tldr-pages/tldr/commit/642dbf2e972e388fab8c84ba3b4685fb862b6454)
[Eduardo Lemos Júnior](mailto:elemosjr@gmail.com) | zip (pt_BR): fix example (#4260) | 2020-08-16T17:26:55 | [cfeb1eaad121](https://github.com/tldr-pages/tldr/commit/cfeb1eaad12153086a0395ec26e384962e78420b)
[Eduardo Lemos Júnior](mailto:elemosjr@gmail.com) | zip, unzip, gzip, tar: add brazilian portuguese translation (#4256) | 2020-08-12T01:33:40 | [fe23465c1841](https://github.com/tldr-pages/tldr/commit/fe23465c1841fae17b27eefa0c39a429236153cf)

