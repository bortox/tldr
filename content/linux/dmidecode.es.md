---
author: ['ferrvic']
date: 1635359738
title: "dmidecode, TLDR Pages"
description: "dmidecode, Muestra la tabla de contenidos del DMI (también conocido como SMBIOS) en un formato legible por humanos."
categories: "linux"
---
> Require de privilegios de root.

> Más información: <https://manned.org/dmidecode>.

- Muestra todos la tabla de contenidos de DMI:

```bash
sudo dmidecode
```

- Muestra la versión de la BIOS:

```bash
sudo dmidecode -s bios-version
```

- Muestra el número de serie del equipo:

```bash
sudo dmidecode -s system-serial-number
```

- Muestra información de la BIOS:

```bash
sudo dmidecode -t bios
```

- Muestra información de la CPU:

```bash
sudo dmidecode -t processor
```

- Muestra información de la memoria:

```bash
sudo dmidecode -t memory
```
Lista de modificaciones realizadas en este archivo


Autor | Descripción | Formato de fecha ISO 8601 | Enlace a GitHub
------|-----|-----|-----
[ferrvic](mailto:73243127+ferrvic@users.noreply.github.com) | dmidecode: add Spanish translation (#7195) | 2021-10-27T20:35:38 | [fcf390d106de](https://github.com/tldr-pages/tldr/commit/fcf390d106de36c3ee3d040631fa7b537e40f5fe)

