---
author: ['Fabio Kleis']
date: 1633313584
title: "lsblk"
description: "lsblk, Lista informações sobre dispositivos."
categories: "linux"
---
> Mais informações: <https://manned.org/lsblk>.

- Lista todos dispositivos de armazenamento no formato de árvore:

```bash
lsblk
```

- Também lista dispositivos vazios:

```bash
lsblk -a
```

- Mostrar a coluna de tamanhos em bytes, em vez de um formato legível por humanos:

```bash
lsblk -b
```

- Mostrar na saída padrão informações sobre os filesystems dos dispositivos:

```bash
lsblk -f
```

- Utiliza caracteres ASCII para o formato de árvore:

```bash
lsblk -i
```

- Mostrar na saída padrão informações sobre block-device topology:

```bash
lsblk -t
```

- Excluír da saída padrão os dispositivos específicados por seus repectivos números separados por vírgulas:

```bash
lsblk -e 1,7
```

- Mostrar um resumo de forma customizada passando as colunas separadas por vírgulas:

```bash
lsblk --output NAME,SERIAL,MODEL,TRAN,TYPE,SIZE,FSTYPE,MOUNTPOINT
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Fabio Kleis](mailto:66813406+Fabiokleis@users.noreply.github.com) | free, lsblk: add pt_BR translation (#6619) | 2021-10-04T04:13:04 | [dad3274aba16](https://github.com/tldr-pages/tldr/commit/dad3274aba16da34388b065f0526fd857970e025)

