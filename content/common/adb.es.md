---
author: ['Moisés Ñañez', 'marchersimon']
date: 1631521281
title: "adb, TLDR Pages"
description: "adb, Android Debug Bridge: comunica con una instancia de un emulador Android o conecta dispositivos Android."
categories: "common"
---
> Algunos subcomandos, como `adb shell`, tienen su propia documentación de uso.

> Más información: <https://developer.android.com/studio/command-line/adb>.

- Verifica si el proceso del servidor adb está ejecutandose y lo inicia:

```bash
adb start-server
```

- Termina el proceso del servidor adb:

```bash
adb kill-server
```

- Inicia una terminal remota en la instance del emulador/dispositivo de destino:

```bash
adb shell
```

- Instala una aplicación Android a un emulador/dispositivo:

```bash
adb install -r ruta/al/archivo.apk
```

- Copia un archivo/directorio desde el dispositivo de destino:

```bash
adb pull ruta/al/archivo_o_directorio_en_el_dispositivo ruta/al/directorio_de_destino_local
```

- Copia un archivo/directorio al dispositivo de destino:

```bash
adb push ruta/al/archivo_o_directorio_local ruta/al/directorio_de_destino_en_el_dispositivo
```

- Obtiene una lista de dispositivos conectados:

```bash
adb devices
```
Lista de modificaciones realizadas en este archivo


Autor | Descripción | Formato de fecha ISO 8601 | Enlace a GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | mention subcommands in every base page (#6383) | 2021-09-13T10:21:21 | [bd677b8b4826](https://github.com/tldr-pages/tldr/commit/bd677b8b48260e301fb99fea794f4dc1458d1562)
[Moisés Ñañez](mailto:moisesnandres@hey.com) | adb: add Spanish translation (#4915) | 2020-11-02T16:25:54 | [c5ad213292fb](https://github.com/tldr-pages/tldr/commit/c5ad213292fb1a4469ab0c331b8634e73a68b237)

