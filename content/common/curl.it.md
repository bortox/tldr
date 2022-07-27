---
author: ['Nicolas Kosinski', 'Marco Bonelli', 'bl-ue']
date: 1620121027
title: "curl, TLDR Pages"
description: "curl, Trasferisci dati da o ad un server."
categories: "common"
---
> Supporta molti protocollo, tra cui HTTP, FTP e POP3.

> Maggiori informazioni: <https://curl.se>.

- Scarica il contenuto di un URL in un file:

```bash
curl http://example.com --output nome_file
```

- Scarica un file, salvando l'output con lo stesso nome indicato nell'URL:

```bash
curl --remote-name http://example.com/nome_file
```

- Scarica un file, seguendo reindirizzamenti, e continuando automaticamente (riprendendo) un trasferimento precedente:

```bash
curl --remote-name --location --continue-at - http://example.com/nome_file
```

- Invia dati form-encoded (richiesta POST di tipo `application/x-www-form-urlencoded`):

```bash
curl --data 'nome=mario' http://example.com/form
```

- Invia una richiesta con un header aggiuntivo, utilizzando un metodo HTTP personalizzato:

```bash
curl --header 'X-Mio-Header: 123' --request PUT http://example.com
```

- Invia dati in formato JSON, specificando l'header content-type appropriato:

```bash
curl --data '{"nome":"mario"}' --header 'Content-Type: application/json' http://example.com/utenti/1234
```

- Utilizza un nome utente ed una password per l'autenticazione con il server:

```bash
curl --user utente:password http://example.com
```

- Utilizza un certificato ed una chiave per una risorsa, ignorando la validazione dei certificati:

```bash
curl --cert client.pem --key chiave.pem --insecure https://example.com
```
Elenco delle modifiche apportate alla documentazione


Autore | Descrizione | Data formato ISO 8601 | Collegamento a GitHub
------|-----|-----|-----
[Nicolas Kosinski](mailto:nicokosi@yahoo.com) | curl: use long arguments (#5872) | 2021-05-04T11:37:07 | [69f02b651045](https://github.com/tldr-pages/tldr/commit/69f02b65104530e9f5d1d32a9528f2d3803050e0)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | curl: update to new 'more information' link (#5254) | 2021-02-07T21:27:41 | [ca9ba675cea1](https://github.com/tldr-pages/tldr/commit/ca9ba675cea1e8accb6121c8c52c4bb273df5163)
[Marco Bonelli](mailto:marco@mebeim.net) | italian pages: add missing homepages. | 2019-06-10T01:35:02 | [55f7679b9d85](https://github.com/tldr-pages/tldr/commit/55f7679b9d85480f6c81738bd32c7901a1db36fe)
[Marco Bonelli](mailto:mb5.marcob@gmail.com) | curl: add Italian translation. | 2019-06-10T01:35:02 | [7c5239fdcd23](https://github.com/tldr-pages/tldr/commit/7c5239fdcd23fc4ecfe920fda61059bd2ab2d9e4)

