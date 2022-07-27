---
author: ['Rafael Julio']
date: 1634641643
title: "fastboot, TLDR Pages"
description: "fastboot, Se comunica com dispositivos Android conectados quando iniciados no modo _fastboot_ (o único lugar em que `adb` não funciona)."
categories: "common"
---
> Mais informações: <https://cs.android.com/android/platform/superproject/+/master:system/core/fastboot>.

- Desbloqueia o bootloader:

```bash
fastboot oem unlock
```

- Bloqueia o bootloader novamente:

```bash
fastboot oem lock
```

- Reinicia o dispositivo no modo fastboot para o modo fastboot novamente:

```bash
fastboot reboot bootloader
```

- Flasheia uma imagem:

```bash
fastboot flash arquivo.img
```

- Flasheia uma imagem de _recovery_ customizada:

```bash
fastboot flash recovery arquivo.img
```

- Exibe os dispositivos conectados:

```bash
fastboot devices
```

- Mostra todas as informações de um dispositivo:

```bash
fastboot getvar all
```
Lista de alterações feitas nesta documentação


Autor | Descrição | Formato de data ISO 8601 | Link para GitHub
------|-----|-----|-----
[Rafael Julio](mailto:development@rafifos.dev) | adb, adb-install, fastboot: add pt_BR translation (#7066) | 2021-10-19T13:07:23 | [70a1e161de41](https://github.com/tldr-pages/tldr/commit/70a1e161de4171f284c3c34860426ba765912427)

