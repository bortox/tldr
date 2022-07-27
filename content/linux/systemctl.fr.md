---
author: ['Alexandre ZANNI']
date: 1633462347
title: "systemctl, TLDR Pages"
description: "systemctl, Contrôle le système systemd et le gestionnaire de services."
categories: "linux"
---
> Plus d'informations : <https://www.freedesktop.org/software/systemd/man/systemctl.html>.

- Liste des unités en échec :

```bash
systemctl --failed
```

- Démarre/arrête/redémarre/recharge un service :

```bash
systemctl start|stop|restart|reload unité
```

- Affiche le statut d'une unité :

```bash
systemctl status unité
```

- Active/désactive une unité à démarrer au démarrage :

```bash
systemctl enable|disable unité
```

- Masque/démasque une unité pour empêcher l'activation et l'activation manuelle :

```bash
systemctl mask|unmask unité
```

- Rechargement de systemd, recherche d'unités nouvelles ou modifiées :

```bash
systemctl daemon-reload
```

- Vérifie si une unité est en cours de fonctionnement :

```bash
systemctl is-active unité
```

- Vérifie si une unité est activée :

```bash
systemctl is-enabled unité
```
Liste des modifications apportées à cette documentation


Auteur | Description | Format de la date ISO 8601 | Lien vers GitHub
------|-----|-----|-----
[Alexandre ZANNI](mailto:16578570+noraj@users.noreply.github.com) | systemctl: add French translation (#6675) | 2021-10-05T21:32:27 | [0cdc5354aba1](https://github.com/tldr-pages/tldr/commit/0cdc5354aba171cb8765ecff71d583c434abe928)

