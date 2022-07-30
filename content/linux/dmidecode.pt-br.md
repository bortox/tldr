---
author: ['Stig124', 'Marco Bonelli']
date: 1625841955
title: "dmidecode"
description: "dmidecode, Exibe em formato de fácil leitura o sumário DMI (também conhecido como SMBIOS) ."
categories: "linux"
---
> Requer privilégio de super usuário.

> Mais informações: <https://manned.org/dmidecode>.

- Exibir o sumário do DMI:

```bash
sudo dmidecode
```

- Exibir a versão da BIOS:

```bash
sudo dmidecode -s bios-version
```

- Exibir o número de série do sistema:

```bash
sudo dmidecode -s system-serial-number
```

- Exibir as informações da BIOS:

```bash
sudo dmidecode -t bios
```

- Exibir as informações da CPU:

```bash
sudo dmidecode -t processor
```

- Exibir as informações da memória:

```bash
sudo dmidecode -t memory
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Stig124](mailto:stigpro@outlook.fr) | linux/[a-g]: add more information link (#6076) | 2021-07-09T16:45:55 | [3697c62b5e5c](https://github.com/tldr-pages/tldr/commit/3697c62b5e5cd9bae7a99c591cb81d1ddcfbf792)
[Marco Bonelli](mailto:marco@mebeim.net) | BCP47 to POSIX: rename Brazilian Portuguese folder. | 2019-08-26T06:23:30 | [54e1ade0a958](https://github.com/tldr-pages/tldr/commit/54e1ade0a958f3a08d9ed60f32b66188d0ecfb63)

