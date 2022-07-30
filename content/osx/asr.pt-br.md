---
author: ['Andreia Bohner']
date: 1658135504
title: "asr"
description: "asr, Restaurar (copiar) uma imagem de disco em um volume."
categories: "osx"
---
> O nome do comando significa Apple Software Restore.

> Mais informações: <https://www.unix.com/man-page/osx/8/asr/>.

- Restaurar uma imagem de disco para um volume de destino:

```bash
sudo asr restore --source nome_da_imagem.dmg --target caminho/para/volume
```

- Apagar o volume de destino antes de restaurar:

```bash
sudo asr restore --source nome_da_imagem.dmg --target caminho/para/volume --erase
```

- Ignorar a verificação após a restauração:

```bash
sudo asr restore --source nome_da_imagem.dmg --target caminho/para/volume --noverify
```

- Clonar volumes sem o uso de uma imagem de disco intermediária:

```bash
sudo asr restore --source caminho/para/volume --target caminho/para/volume_clonado
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Andreia Bohner](mailto:andreiabohner@gmail.com) | asr: add pt_BR translation | 2022-07-18T11:11:44 | [27a589b62da5](https://github.com/tldr-pages/tldr/commit/27a589b62da569fcd3adb2b0dc26de990972205e)

