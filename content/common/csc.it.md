---
author: ['Marco Bonelli', 'Lucas Gabriel Schneider', 'bl-ue']
date: 1621541621
title: "csc, TLDR Pages"
description: "csc, Compilatore per Microsoft C#."
categories: "common"
---
> Maggiori informazioni: <https://docs.microsoft.com/dotnet/csharp/language-reference/compiler-options/command-line-building-with-csc-exe>.

- Compila uno o più file C# in un eseguibile da command-line:

```bash
csc percorso/al/file_input_a.cs percorso/al/file_input_b.cs
```

- Specifica il nome del file output:

```bash
csc /out:percorso/al/nome_file_output percorso/al/file_input.cs
```

- Compila in una libreria `.dll` invece che in un eseguibile:

```bash
csc /target:library percorso/al/file_input.cs
```

- Referenzia un altro assembly:

```bash
csc /reference:percorso/a/libreria.dll percorso/al/file_input.cs
```

- Includi una risorsa:

```bash
csc /resource:percorso/al/file_risorsa percorso/al/file_input.cs
```

- Genera una documentazione XML automaticamente:

```bash
csc /doc:percorso/alla/documentazione.xml percorso/al/file_input.cs
```

- Specifica un'icona:

```bash
csc /win32icon:percorso/a/icona.ico percorso/al/file_input.cs
```

- Firma un assembly con un nome sicuro utilizzando una chiave:

```bash
csc /keyfile:percorso/a/chiave.snk percorso/al/file_input.cs
```
Elenco delle modifiche apportate alla documentazione


Autore | Descrizione | Data formato ISO 8601 | Collegamento a GitHub
------|-----|-----|-----
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | *: fix typos reported by Hunspell (#5848) Co-authored-by: marchersimon <50295997+marchersimon@users.noreply.github.com> Co-authored- [...] | 2021-05-20T22:13:41 | [8ebd171d6f00](https://github.com/tldr-pages/tldr/commit/8ebd171d6f001698709fefc02b1fd5cc9f3a99c4)
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | multiple pages: format technical tokens (#5119) Co-authored-by: bl-ue <54780737+bl-ue@users.noreply.github.com> Co-authored-by: [...] | 2021-01-31T18:05:18 | [a5fe31bc47ae](https://github.com/tldr-pages/tldr/commit/a5fe31bc47aece3efa5e66b52b3cf384f27d5d72)
[Marco Bonelli](mailto:marco@mebeim.net) | italian pages: add missing homepages. | 2019-06-10T01:35:02 | [55f7679b9d85](https://github.com/tldr-pages/tldr/commit/55f7679b9d85480f6c81738bd32c7901a1db36fe)
[Marco Bonelli](mailto:mb5.marcob@gmail.com) | csc: add Italian translation. | 2019-06-10T01:35:02 | [213ccb6f1ac1](https://github.com/tldr-pages/tldr/commit/213ccb6f1ac12993c7c9f3e937dfd2dc9ed62ca5)

