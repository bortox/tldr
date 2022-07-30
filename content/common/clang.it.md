---
author: ['Marco Bonelli']
date: 1560123302
title: "clang"
description: "clang, Compilatore per sorgenti C, C++ ed Objective-C. Può essere usato come alternativa a GCC."
categories: "common"
---
> Maggiori informazioni: <https://clang.llvm.org/docs/ClangCommandLineReference.html>.

- Compila un file sorgente in un binario eseguibile:

```bash
clang sorgente_input.c -o eseguibile_output
```

- Attiva l'output di tutti gli errori ed i warning:

```bash
clang sorgente_input.c -Wall -o eseguibile_output
```

- Includi librerie contenute in un percorso differente da quello del file di sorgente:

```bash
clang sorgente_input.c -o eseguibile_output -Ipercorso_header -Lpercorso_librerie -lnome_libreria
```

- Compila codice sorgente in IR LLVM (Intermediate Representation):

```bash
clang -S -emit-llvm file.c -o file.ll
```
Elenco delle modifiche apportate alla documentazione


Autore | Descrizione | Data formato ISO 8601 | Collegamento a GitHub
------|-----|-----|-----
[Marco Bonelli](mailto:marco@mebeim.net) | italian pages: add missing homepages. | 2019-06-10T01:35:02 | [55f7679b9d85](https://github.com/tldr-pages/tldr/commit/55f7679b9d85480f6c81738bd32c7901a1db36fe)
[Marco Bonelli](mailto:mb5.marcob@gmail.com) | clang: add Italian translation. | 2019-03-03T23:44:18 | [10c9e5fca77c](https://github.com/tldr-pages/tldr/commit/10c9e5fca77cefeef3664f052c126db69b4f8739)

