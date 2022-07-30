---
author: ['Daniel']
date: 1634007925
title: "puppet apply"
description: "puppet apply, Wende ein Puppet-Manifest lokal an."
categories: "common"
---
> Weitere Informationen: <https://puppet.com/docs/puppet/7/man/apply.html>.

- Wende ein Manifest an:

```bash
puppet apply pfad/zu/manifest
```

- Führe Puppetcode aus:

```bash
puppet apply --execute code
```

- Benutze ein bestimmtes Modulverzeichnis und Hiera-Konfigurationsdatei:

```bash
puppet apply --modulepath pfad/zu/ordner --hiera_config pfad/zu/datei pfad/zu/manifest
```
Liste der Änderungen, die an dieser Dokumentation vorgenommen wurden.


Autor | Beschreibung | ISO 8601 Datumsformat | Link zu GitHub
------|-----|-----|-----
[Daniel](mailto:33197631+dadav@users.noreply.github.com) | puppet, puppet-agent, puppet-apply: add page (#6794) | 2021-10-12T05:05:25 | [376a838eabd1](https://github.com/tldr-pages/tldr/commit/376a838eabd1db7407af56860f0f9d26ef02cb9c)

