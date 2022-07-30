---
author: ['Rafael Julio']
date: 1634641643
title: "adb"
description: "adb, Android Debug Bridge: Comunica com uma instância do emulador Android emulator ou dispositivos conectados."
categories: "common"
---
> Alguns subcomandos tais como `adb shell` possuem sua própria documentação de uso.

> Mais informações: <https://developer.android.com/studio/command-line/adb>.

- Checa se o servidor adb está em execução e o iniciar:

```bash
adb start-server
```

- Encerra o processo do servidor adb:

```bash
adb kill-server
```

- Inicia uma shell remota no emulador/dispositivo desejado:

```bash
adb shell
```

- Instala um app Android no emulador/dispositivo:

```bash
adb install -r caminho/para/arquivo.apk
```

- Copia um arquivo/pasta do dispositivo desejado:

```bash
adb pull caminho/para/arquivo_ou_pasta_no_dispositivo caminho/para/pasta_de_destino_local
```

- Copia um arquivo/pasta para o dispositivo desejado:

```bash
adb push caminho/para/arquivo_ou_pasta_local caminho/para/pasta_de_destino_no_dispositivo
```

- Exibe a lista de dispositivos conectados:

```bash
adb devices
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Rafael Julio](mailto:development@rafifos.dev) | adb, adb-install, fastboot: add pt_BR translation (#7066) | 2021-10-19T13:07:23 | [70a1e161de41](https://github.com/tldr-pages/tldr/commit/70a1e161de4171f284c3c34860426ba765912427)

