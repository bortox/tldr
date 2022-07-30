---
author: ['Gabriel Rodrigues']
date: 1634005028
title: "gcalcli"
description: "gcalcli, Ferramenta de linha de comando para interagir com o Google Agenda."
categories: "common"
---
> Solicita autorização da API do Google na primeira inicialização.

> Mais informações: <https://github.com/insanum/gcalcli>.

- Lista seus eventos para todos os seus calendários nos próximos 7 dias:

```bash
gcalcli agenda
```

- Mostra eventos começando em ou entre datas específicas (também recebe datas relativas, por exemplo, "amanhã"):

```bash
gcalcli agenda mm/dd [mm/dd]
```

- Lista eventos de um calendário específico:

```bash
gcalcli --calendar nome_do_calendário agenda
```

- Exibe um calendário ASCII de eventos por semana:

```bash
gcalcli calw
```

- Exibe um calendário ASCII de eventos para um mês:

```bash
gcalcli calm
```

- Adiciona um evento rapidamente ao seu calendário:

```bash
gcalcli --calendar nome_do_calendário quick "mm/dd HH:MM nome_do_evento"
```

- Adiciona um evento ao calendário. Dispara prompt interativo:

```bash
gcalcli --calendar "nome_do_calendário" add
```
List of changes to this documentation


Author | Description | ISO 8601 Date | GitHub link
------|-----|-----|-----
[Gabriel Rodrigues](mailto:gabrxzvski@gmail.com) | gcalcli: add pt_BR translation | 2021-10-12T04:17:08 | [06310c240a34](https://github.com/tldr-pages/tldr/commit/06310c240a346d619e9bd4fd444eadd5699a5d8b)

