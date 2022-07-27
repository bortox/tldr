---
author: ['Marco Bonelli', 'Lucas Gabriel Schneider']
date: 1570455110
title: "calcurse, TLDR Pages"
description: "calcurse, Um calendário e agenda baseados em texto para a linha de comando."
categories: "linux"
---
> Mais informações: <https://calcurse.org>.

- Iniciar o calcurse em modo interativo:

```bash
calcurse
```

- Mostrar os agendamentos e eventos para o presente dia:

```bash
calcurse --appointment
```

- Apagar todos os objetos gravados localmente e importar os objetos remotos:

```bash
calcurse-caldav --init=keep-remote
```

- Apagar todos os objetos remotos e enviar os objetos gravados localmente:

```bash
calcurse-caldav --init=keep-local
```

- Copiar os objetos gravados localmente para o servidor CalDAV e vice-versa:

```bash
calcurse-caldav --init=two-way
```
Lista de alterações feitas nesta documentação


Autor | Descrição | Formato de data ISO 8601 | Link para GitHub
------|-----|-----|-----
[Lucas Gabriel Schneider](mailto:lucas.schneider@sap.com) | multiple pages (pt_BR): fix homepage tokens (#3340) | 2019-10-07T15:31:50 | [83b623d988f7](https://github.com/tldr-pages/tldr/commit/83b623d988f7940581b5e9fbd43ec0fdc7496a68)
[Marco Bonelli](mailto:marco@mebeim.net) | BCP47 to POSIX: rename Brazilian Portuguese folder. | 2019-08-26T06:23:30 | [54e1ade0a958](https://github.com/tldr-pages/tldr/commit/54e1ade0a958f3a08d9ed60f32b66188d0ecfb63)

