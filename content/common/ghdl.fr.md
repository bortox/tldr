---
author: ['Nicolas Kosinski', 'Ivor', 'marchersimon', 'bl-ue', 'Ivor Benderavage']
date: 1633592259
title: "ghdl"
description: "ghdl, Simulateur à source ouvert pour le langage VHDL."
categories: "common"
---
> Plus d'informations : <http://ghdl.free.fr>.

- Analyse un fichier de source VHDL et génère un fichier objet :

```bash
ghdl -a fichier.vhdl
```

- Élabore un design (où `{{design}}` est le nom d'une unité de configuration, d'entité, ou d'architecture) :

```bash
ghdl -e design
```

- Exécute un design élaboré :

```bash
ghdl -r design
```

- Exécute un design élaboré et sauvegarde la sortie à un fichier de forme d'onde :

```bash
ghdl -r design --wave=sortie.ghw
```

- Vérifie le syntaxe d'un fichier de source VHDL :

```bash
ghdl -s fichier.vhdl
```

- Affiche l'aide générale :

```bash
ghdl --help
```
Liste des modifications apportées à cette documentation


Auteur | Description | Format de la date ISO 8601 | Lien vers GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | Replace non-breaking space with regular space in French pages (#6842) | 2021-10-07T09:37:39 | [d63065b882e7](https://github.com/tldr-pages/tldr/commit/d63065b882e77c3d3361e76cfa7f28bf5415832e)
[Nicolas Kosinski](mailto:nicokosi@yahoo.com) | multiple pages: fix typos in French translation (#5841) | 2021-05-01T18:49:31 | [6467b39f66b4](https://github.com/tldr-pages/tldr/commit/6467b39f66b40110a64d13af20f1a7ab27380fa9)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | multiple pages: fix French colon punctuation (#5152) | 2021-01-30T18:03:18 | [5f1ef5bee7db](https://github.com/tldr-pages/tldr/commit/5f1ef5bee7dba1b2749d25e4d0a7be22c89cf8b4)
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | multiple pages: normalize "more information" labels (#5140) | 2021-01-15T18:24:49 | [c59f12aa9f55](https://github.com/tldr-pages/tldr/commit/c59f12aa9f55d85612ba22e4da86db293ff76977)
[Ivor](mailto:ivor.benderavage@gmail.com) | ghdl, git-ignore, ln: add space before colon; ghdl: spelling | 2020-10-19T19:33:37 | [2f2fbcc3e1ef](https://github.com/tldr-pages/tldr/commit/2f2fbcc3e1efb305b5f47f529f91e3bdec4ae2ca)
[Ivor Benderavage](mailto:ivor.benderavage@gmail.com) | ghdl.md: add trailing newline | 2020-10-19T19:33:37 | [561c54e113e7](https://github.com/tldr-pages/tldr/commit/561c54e113e756ba12fffc2bab773290adbb44eb)
[Ivor Benderavage](mailto:ivor.benderavage@gmail.com) | ghdl: add French translation | 2020-10-19T19:33:37 | [12d2b5cf98df](https://github.com/tldr-pages/tldr/commit/12d2b5cf98df55c0264e47d3accee860680f2ffa)

