---
author: ['Schneider', 'Waldir Pimenta', 'Lucas Gabriel Schneider', 'Marco Bonelli']
date: 1612112718
title: "babel"
description: "babel, Un transpiler che converte codice JavaScript da sintassi ES6/ES7 ad ES5."
categories: "common"
---
> Maggiori informazioni: <https://babeljs.io/>.

- Transpila uno specifico file e stampa il risultato su stdout:

```bash
babel percorso/al/file
```

- Transpila un file e scrivi il risultato su uno specifico file di output:

```bash
babel percorso/al/file_input --out-file percorso/al/file_output
```

- Transpila un file ogni volta che viene modificato:

```bash
babel percorso/al/file --watch
```

- Transpila un'intera directory di file:

```bash
babel percorso/a/directory_input
```

- Transpila un'intera directory ignorando specifici file separati da virgola:

```bash
babel percorso/a/directory_input --ignore file_ignorati
```

- Transpila minimizzando il codice JavaScript in output:

```bash
babel percorso/al/file_input --minified
```

- Scegli un insieme di preset per formattare l'output:

```bash
babel percorso/al/file_input --presets preset
```

- Mostra tutte le opzioni disponibili:

```bash
babel --help
```
Elenco delle modifiche apportate alla documentazione


Autore | Descrizione | Data formato ISO 8601 | Collegamento a GitHub
------|-----|-----|-----
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | multiple pages: format technical tokens (#5119) Co-authored-by: bl-ue <54780737+bl-ue@users.noreply.github.com> Co-authored-by: [...] | 2021-01-31T18:05:18 | [a5fe31bc47ae](https://github.com/tldr-pages/tldr/commit/a5fe31bc47aece3efa5e66b52b3cf384f27d5d72)
[Waldir Pimenta](mailto:waldyrious@gmail.com) | Harmonize formatting and capitalization of stdin/stdout/stderr | 2019-06-17T18:39:58 | [cf25745db1d8](https://github.com/tldr-pages/tldr/commit/cf25745db1d86744c762e15e6a2ba04ef9f9acc1)
[Marco Bonelli](mailto:marco@mebeim.net) | Refactor: reword Italian pages' links' descriptions. | 2019-06-03T14:19:41 | [db7959947301](https://github.com/tldr-pages/tldr/commit/db795994730108131d36e7a50b67378e79e27c10)
[Schneider](mailto:lucas.schneider@sap.com) | it\abduco.md: add homepage | 2019-05-14T19:40:23 | [196b44e5109f](https://github.com/tldr-pages/tldr/commit/196b44e5109f9b58f72ac8ba75ec82d395ebf194)
[Marco Bonelli](mailto:mb5.marcob@gmail.com) | babel: add Italian translation. | 2019-01-28T19:10:19 | [48ee4d4f5be1](https://github.com/tldr-pages/tldr/commit/48ee4d4f5be13de8227778ddf481cf6482485bad)

