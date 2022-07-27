---
author: ['Marco Bonelli', 'Franz']
date: 1633438869
title: "dotnet, TLDR Pages"
description: "dotnet, Strumenti .NET da linea di comando multipiattaforma per .NET Core."
categories: "common"
---
> Alcuni comandi aggiuntivi, come `dotnet build`, hanno la propria documentazione.

> Maggiori informazioni: <https://docs.microsoft.com/dotnet/core/tools>.

- Inizializza un nuovo progetto .NET:

```bash
dotnet new nome_abbreviato_template
```

- Ripristina pacchetti nuget:

```bash
dotnet restore
```

- Costruisci ed esegui il progetto .NET nella directory corrente:

```bash
dotnet run
```

- Esegui una applicazione dotnet pacchettizzata (solo il runtime è necessario, il resto dei comandi richiedono .NET Core SDK):

```bash
dotnet percorso/a/applicazione.dll
```
Elenco delle modifiche apportate alla documentazione


Autore | Descrizione | Data formato ISO 8601 | Collegamento a GitHub
------|-----|-----|-----
[Franz](mailto:franz.f1032@gmail.com) | *: mention subcommands in Italian translation (#6804) | 2021-10-05T15:01:09 | [e13e67b1711e](https://github.com/tldr-pages/tldr/commit/e13e67b1711e4112cca0cc4d07521c0cf901290c)
[Marco Bonelli](mailto:marco@mebeim.net) | dotnet: add Italian translation. | 2019-10-05T15:25:51 | [3b3f97d2832e](https://github.com/tldr-pages/tldr/commit/3b3f97d2832e59a2897046e9ba6231e75e1b1e99)

