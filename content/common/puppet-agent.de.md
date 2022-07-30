---
author: ['Daniel']
date: 1634007925
title: "puppet agent"
description: "puppet agent, Ruft die Client-Konfiguration eines Puppetservers ab und setzt diese auf dem System um."
categories: "common"
---
> Weitere Informationen: <https://puppet.com/docs/puppet/7/man/agent.html>.

- Registriere die Node bei einem Puppetserver und wende den empfangenen Katalog an:

```bash
puppet agent --test --server puppetserver_fqdn --serverport port --waitforcert poll_zeit
```

- Führe den Agenten im Hintergrund aus (nutzt die Einstellungen von `/opt/puppetlabs/puppet/puppet.conf`):

```bash
puppet agent
```

- Führe den Agenten einmal im Vordergrund aus und beende:

```bash
puppet agent --test
```

- Führe den Agenten im Dry-Modus aus:

```bash
puppet agent --test --noop
```

- Protokolliere jede ausgewertete Ressource (selbst wenn sich nichts geändert hat):

```bash
puppet agent --test --evaltrace
```
Liste der Änderungen, die an dieser Dokumentation vorgenommen wurden.


Autor | Beschreibung | ISO 8601 Datumsformat | Link zu GitHub
------|-----|-----|-----
[Daniel](mailto:33197631+dadav@users.noreply.github.com) | puppet, puppet-agent, puppet-apply: add page (#6794) | 2021-10-12T05:05:25 | [376a838eabd1](https://github.com/tldr-pages/tldr/commit/376a838eabd1db7407af56860f0f9d26ef02cb9c)

