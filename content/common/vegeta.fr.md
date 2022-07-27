---
author: ['melvinxeu']
date: 1640266666
title: "vegeta, TLDR Pages"
description: "vegeta, Un utilitaire de ligne de commande et une bibliothèque pour les tests de charge HTTP."
categories: "common"
---
> Voir aussi `ab`.

> Plus d'informations : <https://github.com/tsenart/vegeta>.

- Lancer une attaque d'une durée de 30 secondes :

```bash
echo "GET https://exemple.com" | vegeta attack -duration=30s
```

- Lancez une attaque sur un serveur avec un certificat HTTPS auto-signé :

```bash
echo "GET https://exemple.com" | vegeta attack -insecure -duration=30s
```

- Lancer une attaque avec un taux de 10 demandes par seconde :

```bash
echo "GET https://exemple.com" | vegeta attack -duration=30s -rate=10
```

- Lancer une attaque et afficher un rapport :

```bash
echo "GET https://exemple.com" | vegeta attack -duration=30s | vegeta report
```

- Lancer une attaque et reporter les résultats sur un graphique (latence en fonction du temps) :

```bash
echo "GET https://exemple.com" | vegeta attack -duration=30s | vegeta plot > chemin/au/results.html
```

- Lancer une attaque contre plusieurs URL à partir d'un fichier :

```bash
vegeta attack -duration=30s -targets=requetes.txt | vegeta report
```
Liste des modifications apportées à cette documentation


Auteur | Description | Format de la date ISO 8601 | Lien vers GitHub
------|-----|-----|-----
[melvinxeu](mailto:63373444+melvinxeu@users.noreply.github.com) | vegeta: add French translation (#7488) | 2021-12-23T14:37:46 | [c49d016a228e](https://github.com/tldr-pages/tldr/commit/c49d016a228ea70d11c8adffc3327e771d25492f)

