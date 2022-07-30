---
author: ['bl-ue', 'Daan']
date: 1615481685
title: "find"
description: "find, Vind een gespecificieerde string in een bestand."
categories: "windows"
---
> Meer informatie: <https://docs.microsoft.com/windows-server/administration/windows-commands/find>.

- Vind de lijnen dat een specifieke string bevatten:

```bash
find string pad/naar/bestand_of_directory
```

- Laat lijnen zie die de string niet bevatten:

```bash
find string pad/naar/bestand_of_directory /v
```

- Toon het aantal lijnen dat de string bevat:

```bash
find string pad/naar/bestand_of_directory /c
```

- Laat het aantal lijnen zien samen met de lijnen:

```bash
find string pad/naar/bestand_of_directory /n
```
Lijst van wijzigingen die in deze documentatie zijn aangebracht


Auteur | Beschrijving | ISO 8601 datum formaat | Link naar GitHub
------|-----|-----|-----
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | Dutch pages: fix (valid) tldr-lint errors (#5367) | 2021-03-11T17:54:45 | [3c118dd49b8e](https://github.com/tldr-pages/tldr/commit/3c118dd49b8eb927baea1b7795225ef6f3068c58)
[Daan](mailto:9497296+theking465@users.noreply.github.com) | dir, find, rmdir, shutdown: add Dutch translation (#4977) | 2020-11-22T22:54:46 | [5aff6baaffaa](https://github.com/tldr-pages/tldr/commit/5aff6baaffaa2894c5118f0c5bf61b9011fca5fd)

