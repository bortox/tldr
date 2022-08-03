---
date: 2021-11-17
title: "Om TLDR Pages"
description: "Vad är TLDR Pages? Hur kan man bidra? Vad är den här webbplatsen?"
---

> Varning: Den här sidan översätts automatiskt - till skillnad från TLDR Pages på den här webbplatsen - så det kan finnas översättningsfel.

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

## Vad är tldr-pages?

Projektet **tldr-pages** är en samling hjälpsidor som underhålls i samarbete.
för kommandoradsverktyg som utgör ett enklare och mer lättillgängligt komplement till traditionella
till traditionella [man pages](https://en.wikipedia.org/wiki/Man_page).

Kanske är du ny i kommandoradernas värld? Du kanske är lite ringrostig eller inte alltid kommer ihåg argumenten till kommandon som `lsof` eller `tar`?

Det hjälper verkligen inte att det första alternativet som förklaras i `man tar` är:

```
-b block
   Ange blockstorleken, i 512-byte-rekord, för I/O på bandstationen.
   Normalt behövs det här argumentet bara när du läser eller skriver till bandstationer,
   och vanligtvis inte ens då, eftersom standardblockstorleken 20 poster (10240 byte) är mycket vanlig.
```

Det verkar finnas utrymme för enklare hjälpsidor som fokuserar på praktiska exempel.
Vad sägs om:

![animerad SVG av tldr-klienten som visar tar-kommandot](/tldr-tar.svg)

> TLDR-sidan för tar-kommandot finns också på denna webbplats. [denna länk](https://tldr.bortox.it/common/tar)

Det här arkivet är just det: en ständigt växande samling exempel.
för de vanligaste UNIX-, Linux-, macOS-, SunOS-, Android- och Windows-kommandoradsverktygen.

## Vad är den här webbplatsen?

Syftet med den här webbplatsen är att göra TLDR-sidorna, en samling av gemenskapsstyrda hjälpsidor, till en
för kommandoradsverktyg_ för webbanvändare genom att helt enkelt skriva "TLDR pages + command_name" i sin favoritsökmotor.

För närvarande är det inte möjligt att hitta TLDR-sidan för ett kommando med en enkel Google-sökning. Situationen är ännu värre när du söker efter ett kommando på ett annat språk än engelska, eftersom det ofta finns långsamma och clickbait-webbplatser.

Den här webbplatsen stöder även kommentarer och delning, vilket gör TLDR-sidorna "webbvänliga". 

### Analys, övervakning och meddelanden

Naturligtvis finns det ingen **reklam**. 

Spårning sker med Matomo. Matomo är inställt på att inte samla in **personuppgifter**[^1], så det är GDPR-kompatibelt och kräver inte bannercookies. [Om du vill avregistrera dig kan du göra det här](https://stats.bortox.it/index.php?module=CoreAdminHome&action=optOut&language=it).

Webbplatsen är **hyst i Europa**, av PHP-Friends. Enligt web-carbon.com använder datacentret **hållbar energi**!

Om du vill **stödja** webbplatsen (jag betalar för servrarna) kan du [**donera något här**](https://bortox.it/contribuisci-cs-en).

#### Varför den här webbplatsen?

1. indexera TLDR-sidor och göra dem lätt sökbara på nätet på flera språk
2. bara för att skriva något

#### Hur fungerar den här webbplatsen?

* TLDR-källfiler i Markdown och tillhörande Git-data läses från ett skript (30m).
* Hugo-kompatibla sidor skapas av skriptet
* Hugo skapar denna webbplats (~6500 sidor) på bara 10 sekunder!

#### Möjliga nya funktioner

- [ ] Engagemangsspecifika sidor
- Automatisk översättning med DeepL (upp till 500 000 tecken/månad i gratisversionen)


## Hur man använder

Ett populärt och bekvämt sätt att få tillgång till dessa sidor på din egen dator.
är att installera [Node.js-klienten](https://github.com/tldr-pages/tldr-node-client),
som stöds av de ansvariga för tldr-pages-projektet:

``sh
npm install -g tldr
```

Alternativt kan du använda [Python-klienten](https://github.com/tldr-pages/tldr-python-client), som kan installeras via `pip3`.

``sh
pip3 installera tldr
```

Detta ger dig direkt tillgång till en förenklad, lättläst guide till kommandon som `tar`,
tillgänglig genom att skriva `tldr tar` istället för det normala `man tar`.

Om du vill ha en offlineversion utan att installera någon programvara,
se [PDF-version](https://tldr.sh/assets/tldr-book.pdf).

Surfa utan att installera en klient på din dator
se webbklienten på <https://tldr.ostera.io>.

Det finns också **flera andra klienter** som tillhandahålls av gemenskapen,
både för kommandoraden och för andra plattformar.
En fullständig lista över klienter finns i vår [wiki](https://github.com/tldr-pages/tldr/wiki/tldr-pages-clients).


## Hur kan jag bidra till tldr-pages?

Alla bidrag är välkomna!

Du kan bidra på följande sätt

- Lägg till ditt favoritkommando som inte omfattas.
- Lägg till exempel eller förbättra innehållet på en befintlig sida.
- Lägg till begärda sidor från våra utgåvor med etiketten [help wanted](https://github.com/tldr-pages/tldr/issues?q=is%3Aopen+is%3Aissue+label%3A%22help+wanted%22).
- Översättning av sidor till olika språk.

Alla `tldr`-sidor är skrivna i Markdown, så de kan redigeras ganska enkelt och ändringar kan göras i
med Git på kommandoraden eller via
via GitHubs webbgränssnitt.

Vi strävar efter att upprätthålla en [välkomnande och samarbetsvillig](https://github.com/tldr-pages/tldr/blob/main/GOVERNANCE.md) gemenskap.
Om det är första gången du bidrar, ta en titt på [Riktlinjer för bidrag](https://github.com/tldr-pages/tldr/blob/main/CONTRIBUTING.md) och kom igång!

Om du vill bidra till översättningar kan du <https://lukwebsforge.github.io/tldri18n/>
för att se hur det går med alla översättningar och få reda på vilka översättningar som saknas eller är föråldrade.

## Vad betyder "tldr"?

TL;DR står för "Too long; I have not read" (för lång; jag har inte läst).
Det kommer från internetjargongen, där det används för att ange att en lång text (eller delar av den) har
(eller delar av den) har hoppats över eftersom den är för lång.
Mer information i [artikel] av How-To Geek (https://www.howtogeek.com/435266/what-does-tldr-mean-and-how-do-you-use-it/).

[^1]: Inga besökarloggar, spårning utan cookies, anonymiserade IP-adresser (2 bytes, t.ex. 192.168.xxx.xxx ) enligt [official matomo guide](https://matomo.org/faq/new-to-piwik/how-do-i-use-matomo-analytics-without-consent-or-cookie-banner/) ... 