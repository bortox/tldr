---
author: ['Marco Bonelli']
date: 1560123302
title: "csslint"
description: "csslint, Un linter per codice CSS."
categories: "common"
---
> Maggiori informazioni: <https://github.com/CSSLint/csslint/wiki/Command-line-interface>.

- Esegui il linting di un singolo file CSS:

```bash
csslint file.css
```

- Esegui il linting di file CSS multipli:

```bash
csslint file1.css file2.css file3.css
```

- Elenca tutte le possibili regole di stile:

```bash
csslint --list-rules
```

- Specifica certe regole come errori (che risulteranno in un codice d'uscita diverso da zero):

```bash
csslint --errors=errors,universal-selector,imports file.css
```

- Specifica certe regole come warning:

```bash
csslint --warnings=box-sizing,selector-max,floats file.css
```

- Specifica certe regole da essere completamente ignorate:

```bash
csslint --ignore=ids,rules-count,shorthand file.css
```
Elenco delle modifiche apportate alla documentazione


Autore | Descrizione | Data formato ISO 8601 | Collegamento a GitHub
------|-----|-----|-----
[Marco Bonelli](mailto:marco@mebeim.net) | italian pages: add missing homepages. | 2019-06-10T01:35:02 | [55f7679b9d85](https://github.com/tldr-pages/tldr/commit/55f7679b9d85480f6c81738bd32c7901a1db36fe)
[Marco Bonelli](mailto:mb5.marcob@gmail.com) | csslint: add Italian translation. | 2019-06-10T01:35:02 | [2620f67f7e02](https://github.com/tldr-pages/tldr/commit/2620f67f7e022afb3c469da4e52618c63963e933)

