---
author: ['Schneider', 'Marco Bonelli', 'Lucas Gabriel Schneider', 'marchersimon']
date: 1659075216
title: "blender"
description: "blender, Interfaccia da linea di comando per il programma di grafica Blender 3D."
categories: "common"
---
> Gli argomenti sono eseguiti nell'ordine in cui sono dati.

> Maggiori informazioni: <https://manned.org/blender>.

- Renderizza tutti i frame di una animazione in background, senza caricare l'interfaccia grafica (l'output è salvato in `/tmp`):

```bash
blender -b nome_file.blend -a
```

- Renderizza un'animazione usando uno specifico pattern, in un percorso relativo (`//`) al file `.blend`:

```bash
blender -b nome_file.blend -o //render/frame_###.png -a
```

- Renderizza il decimo frame di un'animazione come singola immagine, salvandolo in una cartella esistente (percorso assoluto):

```bash
blender -b nome_file.blend -o /percorso/a/directory_output -f 10
```

- Renderizza il penultimo frame di un'animazione come immagine JPEG, salvandolo in una cartella esistente (path relativa al file):

```bash
blender -b nome_file.blend -o //directory_output -F JPEG -f -2
```

- Renderizza l'animazione di una specifica scena, dal frame 10 al 500:

```bash
blender -b nome_file.blend -S nome_scena -s 10 -e 500 -a
```

- Renderizza un'animazione ad una specifica risoluzione, attraverso l'utilizzo di uno script python:

```bash
blender -b nome_file.blend --python-expr 'import bpy; bpy.data.scenes[0].render.resolution_percentage = 25' -a
```

- Avvia una sessione interattiva di Blender nel terminale con una console python (esegui `import bpy` dopo l'avvio):

```bash
blender -b --python-console
```
Elenco delle modifiche apportate alla documentazione


Autore | Descrizione | Data formato ISO 8601 | Collegamento a GitHub
------|-----|-----|-----
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | Sync more information links with all translations (#8256) | 2022-07-29T08:13:36 | [1f610a952ea0](https://github.com/tldr-pages/tldr/commit/1f610a952ea0d53e0a1bdbd1246ef81f24db2f3f)
[marchersimon](mailto:50295997+marchersimon@users.noreply.github.com) | *: replace dead more information links (#5724) | 2021-07-02T21:22:57 | [6534b52a2ec9](https://github.com/tldr-pages/tldr/commit/6534b52a2ec92c1e691e21901799048c40b069db)
[Lucas Gabriel Schneider](mailto:casdpa@gmail.com) | multiple pages: format technical tokens (#5119) Co-authored-by: bl-ue <54780737+bl-ue@users.noreply.github.com> Co-authored-by: [...] | 2021-01-31T18:05:18 | [a5fe31bc47ae](https://github.com/tldr-pages/tldr/commit/a5fe31bc47aece3efa5e66b52b3cf384f27d5d72)
[Marco Bonelli](mailto:marco@mebeim.net) | Refactor: reword Italian pages' links' descriptions. | 2019-06-03T14:19:41 | [db7959947301](https://github.com/tldr-pages/tldr/commit/db795994730108131d36e7a50b67378e79e27c10)
[Schneider](mailto:lucas.schneider@sap.com) | it\blender.md: add homepage | 2019-05-14T19:40:23 | [a9ddcd839228](https://github.com/tldr-pages/tldr/commit/a9ddcd839228e6316a3cc23aa725dc0fec1cc536)
[Marco Bonelli](mailto:mb5.marcob@gmail.com) | blender: add Italian translation. | 2019-01-28T19:10:19 | [1c3d2f3ee229](https://github.com/tldr-pages/tldr/commit/1c3d2f3ee229ef4cb2622a7b4fd283db14a671c6)

