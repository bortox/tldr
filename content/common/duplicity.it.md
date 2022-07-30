---
author: ['Marco Bonelli']
date: 1570281951
title: "duplicity"
description: "duplicity, Crea archivi incrementali, compressi, cifrati con controllo di versione."
categories: "common"
---
> Può caricare i backup su una varietà di servizi backend.

> Maggiori informazioni: <http://duplicity.nongnu.org>.

- Esegui il backup di una directory via FTPS su una macchina remota, cifrandolo con una password:

```bash
FTP_PASSWORD=password_login_ftp PASSPHRASE=password_cifratura duplicity percorso/a/cartella_sorgente ftps://utente@hostname/percorso/a/cartella_target/
```

- Esegui il backup di una directory in un server Amazon S3, facendo un backup completo ogni mese:

```bash
duplicity --full-if-older-than 1M --use-new-style s3://nome_bucket[/prefisso]
```

- Elimina le versioni più vecchie di un anno da un backup salvato in un server WebDAV:

```bash
FTP_PASSWORD=password_login_webdav duplicity remove-older-than 1Y --force webdav[s]://utente@hostname[:porta]/directory
```

- Elenca i backup disponibili:

```bash
duplicity collection-status "file://percorso/assoluto/a/directory/di/backup"
```

- Elenca i file in un backup salvato su una macchina remota, via SSH:

```bash
duplicity list-current-files --time YYYY-MM-DD scp://utente@hostname/percorso/a/directory/backup
```

- Ripristina una sotto-directory da un backup locale cifrato con GnuPG in una posizione precisa:

```bash
PASSPHRASE=password_chiave_gpg duplicity restore --encrypt-key id_chiave_gpg --file-to-restore percorso/relativo/sotto_directory file://percorso/assoluto/a/directory/di/backup percorso/a/directory/dove/ripristinare
```
Elenco delle modifiche apportate alla documentazione


Autore | Descrizione | Data formato ISO 8601 | Collegamento a GitHub
------|-----|-----|-----
[Marco Bonelli](mailto:marco@mebeim.net) | duplicity: add Italian translation. | 2019-10-05T15:25:51 | [14ec187ced3d](https://github.com/tldr-pages/tldr/commit/14ec187ced3d0827c0f0642967a27dd3261e55b9)

