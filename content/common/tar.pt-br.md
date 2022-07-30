---
author: ["Robby O'Connor", 'bl-ue', 'Eduardo Lemos Júnior', 'Guido Lena Cota']
date: 1615232567
title: "tar"
description: "tar, Ferramenta de compressão de arquivos."
categories: "common"
---
> Utilizado com metodos de compressão como o de gzip ou bzip2.

> Mais informações: <https://www.gnu.org/software/tar>.

- Compactando arquivos em um arquivo tar:

```bash
tar -cvf output.tar arquivo1 arquivo2 arquivo3
```

- Compactando arquivos em arquivo gzip:

```bash
tar -czvf output.tar.gz arquivo1 arquivo2 arquivo3
```

- Compactando arquivos definindo tipo de compressão automaticamente por extensão:

```bash
tar -cavf output.tar.xz arquivo1 arquivo2 arquivo3
```

- Extraindo arquivos de um arquivo compactado:

```bash
tar -xvf input.tar[.gz|.bz2|.xz]
```

- Extraindo arquivos de um arquivo compactado filtrando por gzip:

```bash
tar -xzvf input.tar[.gz|.bz2|.xz]
```

- Extraindo arquivos de um arquivo compactado para um diretório específico:

```bash
tar -xvf input.tar[.gz|.bz2|.xz] -C diretório
```

- Extrair arquivos seguindo um padrão:

```bash
tar -xvf input.tar --wildcards "*.html"
```

- Listando arquivos de um arquivo tar:

```bash
tar -tvf input.tar
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | Portuguese (Brazil) pages: fix (valid) tldr-lint errors (#5369) | 2021-03-08T20:42:47 | [443568f165ec](https://github.com/tldr-pages/tldr/commit/443568f165eccbfa2521da66158f07e4e9d3bd7a)
[Robby O'Connor](mailto:rob@oconnor.ninja) | tar: fix bzip to bzip2 in command description (#5264) | 2021-02-13T04:53:30 | [5cd65c2850e0](https://github.com/tldr-pages/tldr/commit/5cd65c2850e0f3186af032337f596dbb7c5be79a)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | multiple pages: normalize "more information" labels (#5140) | 2021-01-15T18:24:49 | [c59f12aa9f55](https://github.com/tldr-pages/tldr/commit/c59f12aa9f55d85612ba22e4da86db293ff76977)
[Guido Lena Cota](mailto:guido.lenacota@kreuzwerker.de) | Bulk change: move double quotes outside tokens (#4431) | 2020-10-04T19:33:38 | [354d4b8748ee](https://github.com/tldr-pages/tldr/commit/354d4b8748ee58813dd6830ced7c3b11067255d7)
[Eduardo Lemos Júnior](mailto:elemosjr@gmail.com) | zip, unzip, gzip, tar: add brazilian portuguese translation (#4256) | 2020-08-12T01:33:40 | [fe23465c1841](https://github.com/tldr-pages/tldr/commit/fe23465c1841fae17b27eefa0c39a429236153cf)

