---
author: ['Felipe-noob']
date: 1634486785
title: "cp"
description: "cp, Copia arquivos e diretórios."
categories: "linux"
---
> Mais informações: <https://www.gnu.org/software/coreutils/cp>.

- Copiar um arquivo para outra localização:

```bash
cp caminho/para/arquivo_entrada.ext caminho/para/arquivo_saída.ext
```

- Copiar um arquivo para dentro de outro diretório, mantendo o nome:

```bash
cp caminho/para/arquivo.ext caminho/para/diretório
```

- Recursivamente copiar os conteúdos de um diretório para outra localização (se a destinação existe, o diretório é copiado para dentro dela):

```bash
cp -r caminho/para/diretório_fonte caminho/para/diretório_alvo
```

- Copiar um diretório recursivamente, em modo verboso (mostra os arquivos conforme eles são copiados):

```bash
cp -vr caminho/para/diretório_fonte caminho/para/diretório_alvo
```

- Copiar arquivos de texto para outra localização, em modo interativo (exige confirmação do usuário antes de sobrescrever):

```bash
cp -i *.txt caminho/para/diretório_alvo
```

- Seguir links simbólicos antes de copiar:

```bash
cp -L link caminho/para/diretório_alvo
```

- Usar todo o caminho dos arquivos fonte, criando quaisquer diretórios intermediários ausentes quando copia:

```bash
cp --parents fonte/caminho/para/arquivo caminho/para/arquivo_alvo
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Felipe-noob](mailto:80780954+Felipe-noob@users.noreply.github.com) | vlc, ffmpeg, cp: add pt_BR translation (#6608) | 2021-10-17T18:06:25 | [712f84746ac0](https://github.com/tldr-pages/tldr/commit/712f84746ac0ada957e050bc601404d16696b632)

