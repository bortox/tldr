---
date: 2021-11-17
title: "Über TLDR-Seiten"
description: "Was ist TLDR Pages? Wie kann man beitragen? Was ist diese Website?"
---

> Warnung: Diese Seite wird - im Gegensatz zu den TLDR-Seiten auf dieser Website - automatisch übersetzt, daher kann es zu Übersetzungsfehlern kommen.

![TLDR Pages Logo](/tldr-logo.png)

|Gitter|PRs|Contributors|Build Status|LICENSE|
|---|---|---|---|---|
[![Gitter chat][gitter-image]][gitter-url]|[![Merged PRs][prs-merged-image]][prs-merged-url]|[![GitHub contributors][contributors-image]][contributors-url]|[![Build status][github-actions-image]][github-actions-url]|[![license][license-image]][license-url]

[github-actions-url]: https://github.com/tldr-pages/tldr/actions
[github-actions-image]: https://img.shields.io/github/workflow/status/tldr-pages/tldr/CI.svg
[gitter-url]: https://gitter.im/tldr-pages/tldr
[gitter-image]: https://img.shields.io/badge/chat-on_gitter-deeppink
[prs-merged-url]: https://github.com/tldr-pages/tldr/pulls?q=is:pr+is:merged
[prs-merged-image]: https://img.shields.io/github/issues-pr-closed-raw/tldr-pages/tldr.svg?label=merged+PRs&color=green
[contributors-url]: https://github.com/tldr-pages/tldr/graphs/contributors
[contributors-image]: https://img.shields.io/github/contributors-anon/tldr-pages/tldr.svg
[license-url]: https://github.com/tldr-pages/tldr/blob/main/LICENSE.md
[license-image]: https://img.shields.io/badge/license-CC_BY_4.0-blue.svg
</div>



## Was ist tldr-pages?

Das **tldr-pages** Projekt ist eine Sammlung von gemeinschaftlich gepflegten Hilfeseiten
für Befehlszeilen-Tools, die eine einfachere, leichter zugängliche Ergänzung
zu den traditionellen [man pages](https://en.wikipedia.org/wiki/Man_page).

Vielleicht sind Sie neu in der Welt der Kommandozeilen? Vielleicht sind Sie nur ein wenig eingerostet oder können sich nicht immer an die Argumente für Befehle wie `lsof` oder `tar` erinnern?

Es hilft sicherlich nicht, dass die erste Option, die in `man tar` erklärt wird, lautet:

```
-b blockize
   Geben Sie die Blockgröße, in 512-Byte-Sätzen, für die Bandlaufwerk-E/A an.
   In der Regel wird dieses Argument nur beim Lesen von oder Schreiben auf Bandlaufwerke benötigt,
   und normalerweise auch dann nicht, da die Standard-Blockgröße von 20 Sätzen (10240 Bytes) sehr verbreitet ist.
```

Es scheint Raum für einfachere Hilfeseiten zu geben, die sich auf praktische Beispiele konzentrieren.
Wie wäre es mit:

![Animiertes SVG des tldr-Clients, das den tar-Befehl anzeigt](/tldr-tar.svg)

> Die TLDR-Seite zum tar-Befehl ist auch auf dieser Website zu finden [dieser Link](https://tldr.bortox.it/content/common/tar)

Dieses Repository ist genau das: eine ständig wachsende Sammlung von Beispielen
für die gängigsten UNIX-, Linux-, macOS-, SunOS-, Android- und Windows-Kommandozeilen-Tools.

## Was ist diese Website?

Ziel dieser Website ist es, die TLDR Pages, _eine Sammlung von durch die Community gepflegten Hilfeseiten
für Kommandozeilen-Tools_ unter Web-Benutzern zu verbreiten, indem sie einfach "TLDR Pages + command_name" in ihrer bevorzugten Suchmaschine eingeben.

Derzeit kann man mit einer einfachen Google-Suche nicht die TLDR-Seite eines Befehls finden. Noch schlimmer ist es, wenn man einen Befehl in einer bestimmten Sprache sucht, die nicht Englisch ist, da es oft langsame und Clickbait-Websites gibt.

Diese Website unterstützt in der Tat auch Kommentare und das Teilen, so dass TLDR-Seiten auch "webfreundlich" werden. 

### Analytics, Tracking & Anzeigen

Offensichtlich gibt es **keine Werbung**. 

Das Tracking wird mit Matomo durchgeführt. Matomo ist so eingestellt, dass es **keine persönlichen Daten**[^1] sammelt, also GDPR-konform ist und keine Cookie-Banner benötigt. Wenn Sie sich abmelden möchten, [können Sie dies hier tun](https://stats.bortox.it/index.php?module=CoreAdminHome&action=optOut&language=it):

Die Website wird **in Europa** gehostet, von PHP-Friends. Laut website-carbon.com verwendet das Rechenzentrum **nachhaltige Energie**!

Wenn du die Website **unterstützen** willst (ich bezahle für die Server), kannst du [**hier etwas spenden**](https://bortox.it/contribuisci-cs-en).

### Warum diese Website?

1. Um TLDR-Seiten zu indexieren und sie online leicht in mehreren Sprachen durchsuchbar zu machen
2. Nur um etwas zu schreiben

### Wie funktioniert diese Website?

* TLDR-Quelldateien in Markdown und zugehörige Git-Daten werden von einem Skript gelesen (30m)
* Hugo-kompatible Seiten werden durch das Skript erstellt
* Hugo baut diese Website (~6500 Seiten) in nur 10 Sekunden auf!

### Mögliche neue Dinge

- [ ] Commit-spezifische Seiten
- Automatische Übersetzung mit DeepL (bis zu 500.000 Zeichen / Monat in der kostenlosen Version)


## Wie benutze ich es?

Ein beliebter und bequemer Weg, um auf diese Seiten auf Ihrem Computer zuzugreifen
ist die Installation des [Node.js-Client](https://github.com/tldr-pages/tldr-node-client),
der von den Betreuern des tldr-pages-Projekts unterstützt wird:

```sh
npm install -g tldr
```

Alternativ können Sie auch den [Python-Client](https://github.com/tldr-pages/tldr-python-client) verwenden, der über `pip3` installiert werden kann.

```sh
pip3 install tldr
```

Dann haben Sie direkten Zugriff auf eine vereinfachte, leicht zu lesende Hilfe für Befehle, wie `tar`,
zugänglich, indem Sie `tldr tar` anstelle des standardmäßigen `man tar` eingeben.

Wenn Sie eine Offline-Version wünschen, ohne irgendeine Software zu installieren,
sehen Sie sich die [PDF-Version](https://tldr.sh/assets/tldr-book.pdf) an.

Für das Browsen ohne Installation eines Clients auf Ihrem Computer,
siehe den Web-Client unter <https://tldr.ostera.io>.

Es gibt auch **verschiedene andere Clients**, die von der Community bereitgestellt werden,
sowohl für die Befehlszeile als auch für andere Plattformen.
Eine umfassende Liste der Clients finden Sie in unserem [Wiki](https://github.com/tldr-pages/tldr/wiki/tldr-pages-clients).

## Wie kann ich zu tldr-pages beitragen?

Alle Beiträge sind willkommen!

Einige Möglichkeiten, etwas beizutragen, sind

- Hinzufügen Ihres Lieblingsbefehls, der nicht behandelt wird.
- Das Hinzufügen von Beispielen oder die Verbesserung des Inhalts einer bestehenden Seite.
- Hinzufügen von angeforderten Seiten aus unseren Ausgaben mit dem [help wanted](https://github.com/tldr-pages/tldr/issues?q=is%3Aopen+is%3Aissue+label%3A%22help+wanted%22) Label.
- Übersetzen von Seiten in verschiedene Sprachen.

Alle `tldr` Seiten sind in Markdown geschrieben, so dass sie recht einfach bearbeitet werden können und Änderungen können in
mit Git auf der Kommandozeile oder über die
über die GitHub-Weboberfläche eingereicht werden.

Wir bemühen uns, eine [einladende und kollaborative](https://github.com/tldr-pages/tldr/blob/main/GOVERNANCE.md) Gemeinschaft zu pflegen.
Wenn Sie zum ersten Mal einen Beitrag leisten, werfen Sie einen Blick auf die [Beitragsrichtlinien](https://github.com/tldr-pages/tldr/blob/main/CONTRIBUTING.md), und legen Sie los!

Wenn Sie zu Übersetzungen beitragen möchten, können Sie <https://lukwebsforge.github.io/tldri18n/>
besuchen, um den Gesamtfortschritt aller Übersetzungen zu sehen und zu erfahren, welche Übersetzungen fehlen oder veraltet sind.

## Was bedeutet "tldr"?

TL;DR steht für "Too Long; Didn't Read".
Es stammt aus dem Internet-Slang, wo es verwendet wird, um anzuzeigen, dass ein langer Text (oder Teile davon)
(oder Teile davon) übersprungen wurde, weil er zu lang war.
Lesen Sie mehr im [Artikel] von How-To Geek (https://www.howtogeek.com/435266/what-does-tldr-mean-and-how-do-you-use-it/).

[^1]: Kein Besucherprotokoll, kochfreies Tracking, IP-Adressen anonymisiert (2 Bytes, wie 192.168.xxx.xxx ) gemäß [matomo official guide](https://matomo.org/faq/new-to-piwik/how-do-i-use-matomo-analytics-without-consent-or-cookie-banner/) ... 