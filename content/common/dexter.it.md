---
author: ['Marco Bonelli']
date: 1560123302
title: "dexter"
description: "dexter, Strumento per autenticare utenti kubectl con OpenId Connect."
categories: "common"
---
> Maggiori informazioni: <https://github.com/gini/dexter>.

- Crea ed autentica un utente con Google OIDC:

```bash
dexter auth -i id-client -s segreto-client
```

- Sovrascrivi la posizione predefinita della configurazione di kube:

```bash
dexter auth -i id-client -s segreto-client --kube-config percorso/a/config
```
Elenco delle modifiche apportate alla documentazione


Autore | Descrizione | Data formato ISO 8601 | Collegamento a GitHub
------|-----|-----|-----
[Marco Bonelli](mailto:marco@mebeim.net) | italian pages: add missing homepages. | 2019-06-10T01:35:02 | [55f7679b9d85](https://github.com/tldr-pages/tldr/commit/55f7679b9d85480f6c81738bd32c7901a1db36fe)
[Marco Bonelli](mailto:mb5.marcob@gmail.com) | dexter: add Italian translation. | 2019-06-10T01:35:02 | [c439e283b29b](https://github.com/tldr-pages/tldr/commit/c439e283b29b500863f17ae01ec27c8b85d7e14c)

