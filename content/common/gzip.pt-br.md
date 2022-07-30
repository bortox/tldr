---
author: ['Eduardo Lemos Júnior', 'marchersimon']
date: 1618869951
title: "gzip"
description: "gzip, Ferramenta de compactação de arquivos com compressão gzip."
categories: "common"
---
> Mais informações: <https://www.gnu.org/software/gzip/manual/gzip.html>.

- Alterar compressão de um arquivo compactado com compressão gzip:

```bash
gzip arquivo.ext
```

- Descompactar arquivo gzip definindo arquivo final:

```bash
gzip -c -d arquivo.ext.gz > arquivo_descompactado.ext
```

- Compactar arquivo definindo arquivo final:

```bash
gzip -c arquivo.ext > arquivo_compactado.ext.gz
```

- Compactando arquivos em gzip definindo o nível de compressão [9]:

```bash
gzip -9 -c arquivo.ext > arquivo_compactado.ext.gz
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[marchersimon](mailto:marchersimon@zohomail.eu) | add more information links | 2021-04-20T00:05:51 | [bc5d06ed1e1e](https://github.com/tldr-pages/tldr/commit/bc5d06ed1e1e112cfb368a38ae5918ef124cdc22)
[Eduardo Lemos Júnior](mailto:elemosjr@gmail.com) | zip, unzip, gzip, tar: add brazilian portuguese translation (#4256) | 2020-08-12T01:33:40 | [fe23465c1841](https://github.com/tldr-pages/tldr/commit/fe23465c1841fae17b27eefa0c39a429236153cf)

