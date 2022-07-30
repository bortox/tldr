---
author: ['Gustavo Dias Alexandre', 'Rafael Julio', 'marchersimon']
date: 1634641643
title: "adb shell"
description: "adb shell, Android Debug Bridge Shell: Executar remotamente comandos shell em instâncias do emulador Android ou dispositivos Android conectados."
categories: "common"
---
> Mais informações: <https://developer.android.com/studio/command-line/adb>.

- Inicia um shell interativo remoto no emulador/dispositivo:

```bash
adb shell
```

- Obtém todas as propriedades do emulador ou dispositivo:

```bash
adb shell getprop
```

- Reverte todas as permissões de tempo de execução para o padrão:

```bash
adb shell pm reset-permissions
```

- Revoga uma permissão perigosa para um aplicação:

```bash
adb shell pm revoke pacote permissao
```

- Aciona um evento:

```bash
adb shell input keyevent keycode
```

- Limpa os dados da aplicação no emulador/dispositivo:

```bash
adb shell pm clear pacote
```

- Inicia uma atividade no emulator/dispositivo:

```bash
adb shell am start -n pacote/atividade
```

- Inicia atividade "home" no emulator/dispositivo:

```bash
adb shell am start -W -c android.intent.category.HOME -a android.intent.action.MAIN
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Rafael Julio](mailto:development@rafifos.dev) | adb, adb-install, fastboot: add pt_BR translation (#7066) | 2021-10-19T13:07:23 | [70a1e161de41](https://github.com/tldr-pages/tldr/commit/70a1e161de4171f284c3c34860426ba765912427)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: sync more information links in translations (#6537) | 2021-10-01T20:28:01 | [642dbf2e972e](https://github.com/tldr-pages/tldr/commit/642dbf2e972e388fab8c84ba3b4685fb862b6454)
[Gustavo Dias Alexandre](mailto:gfdiasa@gmail.com) | adb-shell: add pt_BR translation (#4395) | 2020-10-01T23:06:39 | [6caa800e7e91](https://github.com/tldr-pages/tldr/commit/6caa800e7e919df783e1acbc1d6477d99f36fdfb)

