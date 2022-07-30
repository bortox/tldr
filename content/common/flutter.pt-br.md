---
author: ['Pedro Zaroni']
date: 1634910961
title: "flutter"
description: "flutter, SDK livre e open source do Google para desenvolvimento de aplicativos mobile cross-platform."
categories: "common"
---
> Mais informações: <https://github.com/flutter/flutter/wiki/The-flutter-tool>.

- Mostra ajuda sobre algum comando específico:

```bash
flutter help comando
```

- Verifica se todas as ferramentas externas necessárias estão instaladas:

```bash
flutter doctor
```

- Lista ou muda o channel do Flutter:

```bash
flutter channel stable|beta|dev|master
```

- Executa o projeto Flutter em todos os emuladores ativos ou devices conectados:

```bash
flutter run -d all
```

- Instala todas as dependências definidas no `pubspec.yaml`:

```bash
flutter pub get
```

- Executa todos os testes no terminal a partir da raíz do projeto:

```bash
flutter test test/example_test.dart
```

- Buildar APK de release direcionado aos mais modernos smartphones:

```bash
flutter build apk --target-platform android-arm,android-arm64
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Pedro Zaroni](mailto:pedro.zaroni@quintoandar.com.br) | flutter: add pt_BR translation (#7033) | 2021-10-22T15:56:01 | [c6e33e93cbed](https://github.com/tldr-pages/tldr/commit/c6e33e93cbed284cf5f1c7fe59af52dbc27a259e)

