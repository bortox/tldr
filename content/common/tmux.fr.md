---
author: ['arnaudvalle', 'bl-ue', 'marchersimon']
date: 1633592259
title: "tmux, TLDR Pages"
description: "tmux, Multiplexeur de terminaux. Permet plusieurs sessions avec fenêtres, panneaux, et plus encore."
categories: "common"
---
> Plus d'informations : <https://github.com/tmux/tmux>.

- Démarrer une nouvelle session :

```bash
tmux
```

- Démarrer une nouvelle session nommée :

```bash
tmux new-session -s nom
```

- Lister les sessions existantes :

```bash
tmux ls
```

- S'attacher à la session utilisée la plus récemment :

```bash
tmux attach-session
```

- S'attacher à une session nommée :

```bash
tmux attach-session -t nom
```

- Se détacher de la session actuelle (avec le préfixe Ctrl-B) :

```bash
Ctrl-B d
```

- Détruire une session nommée :

```bash
tmux kill-session -t nom
```

- Détruire la session actuelle (avec le préfixe Ctrl-B) :

```bash
Ctrl-B :kill-session<Enter>
```
Liste des modifications apportées à cette documentation


Auteur | Description | Format de la date ISO 8601 | Lien vers GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | Replace non-breaking space with regular space in French pages (#6842) | 2021-10-07T09:37:39 | [d63065b882e7](https://github.com/tldr-pages/tldr/commit/d63065b882e77c3d3361e76cfa7f28bf5415832e)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | multiple pages: fix French colon punctuation (#5152) | 2021-01-30T18:03:18 | [5f1ef5bee7db](https://github.com/tldr-pages/tldr/commit/5f1ef5bee7dba1b2749d25e4d0a7be22c89cf8b4)
[arnaudvalle](mailto:arnaudvalle@users.noreply.github.com) | tmux: add French translation (#4720) | 2020-10-19T18:48:54 | [df777ff247bb](https://github.com/tldr-pages/tldr/commit/df777ff247bb0b52351593512dea6805f5a0cc11)

