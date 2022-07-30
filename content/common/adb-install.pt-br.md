---
author: ['Rafael Julio']
date: 1634641643
title: "adb install"
description: "adb install, Android Debug Bridge Install: Instalar apps em uma instância do Android emulator ou dispositivos conectados."
categories: "common"
---
> Mais informações: <https://developer.android.com/studio/command-line/adb>.

- Instala um app Android em um emulador/dispositivo:

```bash
adb install caminho/para/arquivo.apk
```

- Reinstala um app existente, mantendo seus dados:

```bash
adb install -r caminho/para/arquivo.apk
```

- Concede todas as permissões listadas no manifesto do app:

```bash
adb install -g caminho/para/arquivo.apk
```

- Atualiza rapidamente um app já instalado atualizando apenas as partes do APK que mudaram:

```bash
adb install --fastdeploy caminho/para/arquivo.apk
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Rafael Julio](mailto:development@rafifos.dev) | adb, adb-install, fastboot: add pt_BR translation (#7066) | 2021-10-19T13:07:23 | [70a1e161de41](https://github.com/tldr-pages/tldr/commit/70a1e161de4171f284c3c34860426ba765912427)

