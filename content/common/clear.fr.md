---
author: ['Nicolas Kosinski', 'bl-ue', 'marchersimon', 'julien']
date: 1633592259
title: "clear, TLDR Pages"
description: "clear, Efface l'écran du terminal."
categories: "common"
---
> Plus d'informations : <https://manned.org/clear>.

- Effacer l'écran (identique à la séquence Contrôle-L sur une interface bash) :

```bash
clear
```

- Effacer l'écran mais conserve le tampon de défilement du terminal :

```bash
clear -x
```

- Indiquer le type de terminal à effacer (utilise par défaut la variable d'environnement `TERM`) :

```bash
clear -T type_de_terminal
```

- Afficher la version de `ncurses` utilisée par `clear` :

```bash
clear -V
```
Liste des modifications apportées à cette documentation


Auteur | Description | Format de la date ISO 8601 | Lien vers GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | Replace non-breaking space with regular space in French pages (#6842) | 2021-10-07T09:37:39 | [d63065b882e7](https://github.com/tldr-pages/tldr/commit/d63065b882e77c3d3361e76cfa7f28bf5415832e)
[Nicolas Kosinski](mailto:nicokosi@yahoo.com) | atom, clear, convert, df: sync French translations with English pages (#5797) | 2021-04-20T20:15:58 | [df7770ae6b58](https://github.com/tldr-pages/tldr/commit/df7770ae6b585a043f7a797de941a1c425acc6a5)
[marchersimon](mailto:marchersimon@zohomail.eu) | replace `man.archlinux.org` with `manned.org` | 2021-04-18T16:33:27 | [9abb079afb69](https://github.com/tldr-pages/tldr/commit/9abb079afb6972f3de61a30e1b3fb849ad4b68d9)
[marchersimon](mailto:marchersimon@zohomail.eu) | clear: add link | 2021-04-18T16:33:27 | [907b82779088](https://github.com/tldr-pages/tldr/commit/907b827790882ee9086eb4d20cf8e3059343048a)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | multiple pages: fix French colon punctuation (#5152) | 2021-01-30T18:03:18 | [5f1ef5bee7db](https://github.com/tldr-pages/tldr/commit/5f1ef5bee7dba1b2749d25e4d0a7be22c89cf8b4)
[julien](mailto:git@julienc.io) | clear: add French translation | 2019-10-27T17:33:39 | [ca7c406cda0b](https://github.com/tldr-pages/tldr/commit/ca7c406cda0ba6724d9bbd2f720b1072fcfd4854)

