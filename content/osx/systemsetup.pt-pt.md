---
author: ['meowmeowcat', 'Rúben Silva', 'marchersimon']
date: 1659075216
title: "systemsetup, TLDR Pages"
description: "systemsetup, Configura as definições de Preferencias do Sistema da máquina"
categories: "osx"
---
> Mais informações: <https://support.apple.com/guide/remote-desktop/about-systemsetup-apd95406b8d/mac>.

- Ativa autenticação remota (SSH):

```bash
systemsetup -setremotelogin on
```

- Ativa o serviço de hora de rede com um fuso horário e servidor específico:

```bash
systemsetup -settimezone Europe/Lisbon -setnetworktimeserver 2.pt.pool.ntp.org -setusingnetworktime on
```

- Colaca a máquina sem dormir, reiniciando automaticamente em falta de energia ou pânico do núcleo do sistema:

```bash
systemsetup -setsleep off -setrestartpowerfailure on -setrestartfreeze on
```

- Lista os discos de inicialização validos:

```bash
systemsetup -liststartupdisks
```

- Especifica um novo disco de inicialização:

```bash
systemsetup -setstartupdisk caminho
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | Sync more information links with all translations (#8256) | 2022-07-29T08:13:36 | [1f610a952ea0](https://github.com/tldr-pages/tldr/commit/1f610a952ea0d53e0a1bdbd1246ef81f24db2f3f)
[meowmeowcat](mailto:meowmeowcat1211@gmail.com) | osx/s*: add link (#7428) | 2021-11-14T20:45:59 | [a36f8550d81b](https://github.com/tldr-pages/tldr/commit/a36f8550d81be6fbe04cb43f3d0a34f30e024b86)
[Rúben Silva](mailto:rubensilva945@gmail.com) | scutil, screencapture, systemsetup, ..: add pt_PT translation (#7088) | 2021-11-04T20:33:02 | [835c489a199f](https://github.com/tldr-pages/tldr/commit/835c489a199f47ee2018b55dafa537df727623fe)

