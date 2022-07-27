---
author: ['Simone Ragusa']
date: 1619003118
title: "age, TLDR Pages"
description: "age, Uno strumento semplice, moderno e sicuro per la cifratura di file."
categories: "common"
---
> Maggiori informazioni: <https://age-encryption.org>.

- Generare un file cifrato che può essere decifrato con una passphrase:

```bash
age --passphrase --output percorso/del/file_cifrato percorso/del/file_non_cifrato
```

- Generare una coppia di chiavi, salvando la chiave privata in un file non cifrato e stampando sullo stdout la chiave pubblica:

```bash
age-keygen --output percorso/del/file
```

- Cifrare un file con una o più chiavi pubbliche inserite come letterali:

```bash
age --recipient chiave_pubblica_1 --recipient chiave_pubblica_2 percorso/del/file_non_cifrato --output percorso/del/file_cifrato
```

- Cifrare un file con una o più chiavi pubbliche specificate in un file di destinatari:

```bash
age --recipients-file percorso/del/file_di_destinatari percorso/del/file_non_cifrato --output percorso/del/file_cifrato
```

- Decifrare un file con una passphrase:

```bash
age --decrypt --output percorso/del/file_decifrato percorso/del/file_cifrato
```

- Decifrare un file con il file di una chiave privata:

```bash
age --decrypt --identity percorso/del/file_chiave_privata --output percorso/del/file_decifrato percorso/del/file_cifrato
```
Elenco delle modifiche apportate alla documentazione


Autore | Descrizione | Data formato ISO 8601 | Collegamento a GitHub
------|-----|-----|-----
[Simone Ragusa](mailto:simone99.as@gmail.com) | age: add Italian translation | 2021-04-21T13:05:18 | [ad9f6c6c84d3](https://github.com/tldr-pages/tldr/commit/ad9f6c6c84d35b8352d541a3a19f12b251cc34bf)

