---
author: ['FantasyCookie17', 'Andrea']
date: 1619634874
title: "cp"
description: "cp, Copia file e cartelle."
categories: "linux"
---
> Maggiori informazioni: <https://www.gnu.org/software/coreutils/cp>.

- Copia un file in un'altra posizione:

```bash
cp persorso/al/file_da_copiare.est percorso/al/file_di_destinazione.est
```

- Copia un file all'interno di una cartella, mantenendone uguale il nome:

```bash
cp percorso/al/file_da_copiare.est percorso/alla/cartella
```

- Copia ricorsivamente i contenuti di una cartella in un'altra posizione (se la destinazione esiste, la cartella è copiata al suo interno):

```bash
cp -r percorso/alla/cartella_da_copiare percorso/di/destinazione
```

- Copia una cartella ricorsivamente in modalità prolissa (mostra i file mentre vengono copiati):

```bash
cp -vr percorso/alla/cartella_da_copiare percorso/di/destinazione
```

- Copia i file di testo in un'altra posizione, in modalità interattiva (richiede conferma all'utente prima di sovrascrivere):

```bash
cp -i *.txt percorso/di/destinazione
```

- Segue i collegamenti simbolici prima di copiare:

```bash
cp -L collegamento percorso/di/destinazione
```

- Utilizza il percorso completo dei file originali, creando ogni cartella intermedia mancante mentre durante la copia:

```bash
cp --parents percorso/dei/file/da/copiare percorso/al/file/destinazione
```
Elenco delle modifiche apportate alla documentazione


Autore | Descrizione | Data formato ISO 8601 | Collegamento a GitHub
------|-----|-----|-----
[FantasyCookie17](mailto:fantasycookie17@artemislena.eu) | cp: add more information link (#5853) | 2021-04-28T20:34:34 | [d03a29e4109e](https://github.com/tldr-pages/tldr/commit/d03a29e4109ee52e0a30835124691d6f8f187346)
[Andrea](mailto:agnophi@gmail.com) | acpi, adduser, cp, fsck, halt, lsmod, lsusb, mkfs, modinfo, modprobe, pidof, poweroff: add Italian translation | 2020-10-28T18:59:18 | [78a1f4ce6b47](https://github.com/tldr-pages/tldr/commit/78a1f4ce6b4737c3049ec89305ab9a6f1ba54601)

