---
author: ['Nicolas Kosinski', 'Agno94']
date: 1620113149
title: "wget, TLDR Pages"
description: "wget, Scarica file dal Web."
categories: "common"
---
> Supporta HTTP, HTTPS, FTP.

> Maggiori informazioni: <https://www.gnu.org/software/wget>.

- Scarica il contenuto dell'URL in un file (dal nome "abcd" in questo caso):

```bash
wget https://esempio.com/abcd
```

- Scarica il contenuto dell'URL in un file (dal nome "efgh" in questo caso):

```bash
wget --output-document efgh https://esempio.com/abcd
```

- Scarica una singola pagina web e tutte le sue risorse (script, immagini, stili, ecc..) aspettando 3 secondi dopo ogni richiesta:

```bash
wget --page-requisites --convert-links --wait=3 https://esempio.com/pagina_web.html
```

- Scarica tutti i file elencati nella cartella e nelle sue sotto-cartelle (non scarica gli elementi incorporati nella pagina):

```bash
wget --mirror --no-parent https://esempio.com/unqualchepercorso/
```

- Limita la velocità di download e il numero di tentativi di connessione:

```bash
wget --limit-rate=300k --tries=100 https://esempio.com/unqualchepercorso/
```

- Scarica un file da un server HTTP trasmettendo le credenziali tramite Basis Auth (funzione anche con FTP):

```bash
wget --user=nome_utente --password=password https://esempio.com
```

- Riprende un download incompleto:

```bash
wget --continue https://esempio.com
```

- Scarica tutti gli URL contenuti in un file di testo in una cartella specificata:

```bash
wget --directory-prefix percorso/alla/cartella --input-file lista_di_URL.txt
```
Elenco delle modifiche apportate alla documentazione


Autore | Descrizione | Data formato ISO 8601 | Collegamento a GitHub
------|-----|-----|-----
[Nicolas Kosinski](mailto:nicokosi@yahoo.com) | wget: use long arguments (#5879) | 2021-05-04T09:25:49 | [5d01dae43fae](https://github.com/tldr-pages/tldr/commit/5d01dae43fae9f8dcf5d5f1d7df2d7104ece7907)
[Agno94](mailto:agnophi@gmail.com) | ffprobe, flac, id3tag, opusenc, vlc, wget, youtube-dl: add Italian translation (#4869) | 2020-11-02T13:07:44 | [e9eb628533b3](https://github.com/tldr-pages/tldr/commit/e9eb628533b31c09c5951ffa57f4194be88d8f63)

