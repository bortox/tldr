---
author: ['Daan', 'bl-ue']
date: 1615481685
title: "shutdown, TLDR Pages"
description: "shutdown, Een tool om een machine af te sluiten, her op te starten of af te melden."
categories: "windows"
---
> Meer informatie: <https://docs.microsoft.com/windows-server/administration/windows-commands/shutdown>.

- Sluit de huidige machine af:

```bash
shutdown /s
```

- Sluit de huidige machine af en sluit alle applicaties:

```bash
shutdown /s /f
```

- Herstart de huidige machine:

```bash
shutdown /r /t 0
```

- Zet de huidige machine in slaapstand:

```bash
shutdown /h
```

- Log uit van de huidige machine:

```bash
shutdown /l
```

- Zet een timer in aantal seconden voor het afsluiten van de huidige machine:

```bash
shutdown /s /t seconden
```

- Breek een afsluit sequentie af vooraleer de timer was afgelopen:

```bash
shutdown /a
```

- Sluit een machine af op afstand:

```bash
shutdown /m \\hostnaam
```
Lijst van wijzigingen die in deze documentatie zijn aangebracht


Auteur | Beschrijving | ISO 8601 datum formaat | Link naar GitHub
------|-----|-----|-----
[bl-ue](mailto:54780737+bl-ue@users.noreply.github.com) | Dutch pages: fix (valid) tldr-lint errors (#5367) | 2021-03-11T17:54:45 | [3c118dd49b8e](https://github.com/tldr-pages/tldr/commit/3c118dd49b8eb927baea1b7795225ef6f3068c58)
[Daan](mailto:9497296+theking465@users.noreply.github.com) | dir, find, rmdir, shutdown: add Dutch translation (#4977) | 2020-11-22T22:54:46 | [5aff6baaffaa](https://github.com/tldr-pages/tldr/commit/5aff6baaffaa2894c5118f0c5bf61b9011fca5fd)

