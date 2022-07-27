---
author: ['melvinxeu', 'lincc']
date: 1643487459
title: "age, TLDR Pages"
description: "age, Un outil de cryptage de fichiers simple, moderne et sécurisé."
categories: "common"
---
> Plus d'informations : <https://age-encryption.org>.

- Générez un fichier crypté qui peut être décrypté avec une mot de passe:

```bash
age --passphrase --output chemin/vers/fichier_crypté chemin/vers/fichier_non_crypté
```

- Générer une paire de clés, en enregistrant la clé privée dans un fichier non crypté et en imprimant la clé publique sur stdout:

```bash
age-keygen --output chemin/vers/fichier
```

- Cryptage d'un fichier avec une ou plusieurs clés publiques qui sont entrées comme des littéraux:

```bash
age --recipient clé_publique_1 --recipient clé_publique_2 chemin/vers/fichier_non_crypté --output chemin/vers/fichier_crypté
```

- Cryptez un fichier avec une ou plusieurs clés publiques spécifiées dans un fichier de destinataires:

```bash
age --recipients-file chemin/vers/fichier_destinataire chemin/vers/fichier_non_crypté --output chemin/vers/fichier_crypté
```

- Déchiffrer un fichier avec un mot de passe:

```bash
age --decrypt --output chemin/vers/fichier_décrypté chemin/vers/fichier_crypté
```

- Decrypt a file with a private key file:

```bash
age --decrypt --identity chemin/vers/fichier_clé_privée --output chemin/vers/fichier_décrypté chemin/vers/fichier_crypté
```
Liste des modifications apportées à cette documentation


Auteur | Description | Format de la date ISO 8601 | Lien vers GitHub
------|-----|-----|-----
[lincc](mailto:46962923+blueskyson@users.noreply.github.com) | *: update links via set-more-info-link.py (#7611) | 2022-01-29T21:17:39 | [b99f3da787c6](https://github.com/tldr-pages/tldr/commit/b99f3da787c6f43a545b9cb5ebd8265b1367fbc4)
[melvinxeu](mailto:63373444+melvinxeu@users.noreply.github.com) | age: french translation (#7489) | 2021-12-12T15:47:34 | [9b7facc32af2](https://github.com/tldr-pages/tldr/commit/9b7facc32af227421f2aed3806c5a35ffd8b7002)

