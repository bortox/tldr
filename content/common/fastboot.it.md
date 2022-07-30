---
author: ['Andrea', 'bl-ue', 'Rafael Julio']
date: 1634730630
title: "fastboot"
description: "fastboot, Comunica con il dispositivo Android connessione quando in modalità bootloader (la situazione in cui `adb` non funziona)."
categories: "common"
---
> Maggiori informazioni: <https://cs.android.com/android/platform/superproject/+/master:system/core/fastboot>.

- Sblocca il bootloader:

```bash
fastboot oem unlock
```

- Ri-blocca il bootloader:

```bash
fastboot oem lock
```

- Riavvia il dispositivo da modalità fastboot, nuovamente in modalità fastboot:

```bash
fastboot reboot bootloader
```

- Esegue in Flash di una data immagine:

```bash
fastboot flash file.img
```

- Esegue il Flash di una recovery image personalizzata:

```bash
fastboot flash recovery file.img
```

- Mostra i dispositivi connessi:

```bash
fastboot devices
```

- Mostra tutte le informazioni su un dispositivo:

```bash
fastboot getvar all
```
Elenco delle modifiche apportate alla documentazione


Autore | Descrizione | Data formato ISO 8601 | Collegamento a GitHub
------|-----|-----|-----
[Rafael Julio](mailto:development@rafifos.dev) | bugreport, bugreportz, fastboot: use links to code search (#7074) | 2021-10-20T13:50:30 | [e48d44f376dd](https://github.com/tldr-pages/tldr/commit/e48d44f376dd7610f183ca3d490fe9adfcf3e518)
[Rafael Julio](mailto:development@rafifos.dev) | adb, adb-install, fastboot: add pt_BR translation (#7066) | 2021-10-19T13:07:23 | [70a1e161de41](https://github.com/tldr-pages/tldr/commit/70a1e161de4171f284c3c34860426ba765912427)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | *: trim multiple spaces, fix line endings | 2021-04-04T01:44:24 | [04dd546e2de7](https://github.com/tldr-pages/tldr/commit/04dd546e2de7f59f40a867acca6f46b0dc8ea9b4)
[Andrea](mailto:agnophi@gmail.com) | fastboot: add italian translation | 2020-10-28T18:42:52 | [dfaeee1a6986](https://github.com/tldr-pages/tldr/commit/dfaeee1a6986c12d1dd01ea9afc734c0b88f89aa)

