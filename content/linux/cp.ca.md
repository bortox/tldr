---
author: ['Seifer23']
date: 1644117941
title: "cp, TLDR Pages"
description: "cp, Còpia arxius i directoris."
categories: "linux"
---
> Més informació: <https://www.gnu.org/software/coreutils/cp>.

- Copia un arxiu a un altre directori:

```bash
cp ruta/al/arxiu_origen.ext ruta/al/archiu_destí.ext
```

- Copia un archivo en otro directorio, conservando el nombre del archivo:

```bash
cp ruta/al/arxiu_origen.ext ruta/al/directori_destinatari
```

- Còpia de forma recursiva el contingut d'un directori a una altra ubicació (si el destí existeix, el directori és copiat en aquesta ubicació):

```bash
cp -r ruta/al/directori_origen ruta/al/directori_destinatari
```

- Còpia un directori de forma recursiva en mode verbose (mostra els arxius a mesura que es copien):

```bash
cp -vr ruta/al/directori_origen ruta/al/directori_destinatari
```

- Còpia arxius de text en una altra ubicació en mode interactiu (pregunta al usuari abans de sobreescriure):

```bash
cp -i *.txt ruta/al/directori_destinatari
```

- Segueix els enllaços simbòlics abans de copiar:

```bash
cp -L link ruta/al/directori_destinatari
```

- Utilitza la ruta completa dels arxius d'origen, creant els directoris intermitjos faltants al copiar:

```bash
cp --parents ruta_de_origen/al/archiu ruta/al/archiu_destí
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Seifer23](mailto:48915360+Seifer23@users.noreply.github.com) | *: add Catalan translation (#7736) | 2022-02-06T04:25:41 | [99db37b3afd6](https://github.com/tldr-pages/tldr/commit/99db37b3afd6dba836a6d94e4688601fdb3bac98)

