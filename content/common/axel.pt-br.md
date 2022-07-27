---
author: ['Marco Bonelli']
date: 1566793410
title: "axel, TLDR Pages"
description: "axel, Acelerador de downloads."
categories: "common"
---
> Suporta HTTP, HTTPS, e FTP.

> Mais informações: <https://github.com/axel-download-accelerator/axel>.

- Fazer download de uma URL para um arquivo:

```bash
axel url
```

- Fazer download especificando o nome do arquivo de destino:

```bash
axel url -o nome_do_arquivo
```

- Fazer download usando múltiplas conexões:

```bash
axel -n número_de_conexões url
```

- Procurar por mirrors:

```bash
axel -S número_de_mirrors url
```

- Limitar velocidade de download (em bytes por segundo):

```bash
axel -s velocidade url
```
Lista de alterações feitas nesta documentação


Autor | Descrição | Formato de data ISO 8601 | Link para GitHub
------|-----|-----|-----
[Marco Bonelli](mailto:marco@mebeim.net) | BCP47 to POSIX: rename Brazilian Portuguese folder. | 2019-08-26T06:23:30 | [54e1ade0a958](https://github.com/tldr-pages/tldr/commit/54e1ade0a958f3a08d9ed60f32b66188d0ecfb63)

