---
author: ['Luis Braschi']
date: 1660918834
title: "alien"
description: "alien, Converter diferentes pacotes de instalação para outros formatos."
categories: "linux"
---
> Mais informações: <https://manned.org/alien>.

- Converter um arquivo de instalação específico para o formato Debian (extensão `.deb`):

```bash
sudo alien --to-deb caminho/para/arquivo
```

- Converter um arquivo de instalação específico para o formato Red Hat (extensão `.rpm`):

```bash
sudo alien --to-rpm caminho/para/arquivo
```

- Converter um arquivo de instalação específico para um arquivo de instalação do Slackware (extensão `.tgz`):

```bash
sudo alien --to-tgz caminho/para/arquivo
```

- Converter um arquivo de instalação específico para o formato Debian e instalar no sistema:

```bash
sudo alien --to-deb --install caminho/para/arquivo
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Luis Braschi](mailto:CasperBraske@users.noreply.github.com) | alien: add pt_BR translation (#8376) | 2022-08-19T16:20:34 | [0cf74cf39b36](https://github.com/tldr-pages/tldr/commit/0cf74cf39b362570f5d36f935498af3070b6c7e2)

