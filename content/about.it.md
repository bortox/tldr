---
date: 2021-11-17
title: "Informazioni sulle pagine TLDR"
description: "Che cos'è TLDR Pages? Come contribuire? Che cos'è questo sito?"
---

> Attenzione: questa pagina è tradotta automaticamente - a differenza di altre pagine TLDR in questo sito - quindi potrebbero esserci degli errori di traduzione.

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






## Che cos'è tldr-pages?

Il progetto **tldr-pages** è una raccolta di pagine di aiuto gestite in modo collaborativo.
per gli strumenti a riga di comando che forniscono un complemento più semplice e accessibile ai tradizionali strumenti di
alle tradizionali [pagine man](https://en.wikipedia.org/wiki/Man_page).

Forse siete nuovi al mondo delle linee di comando? Forse siete un po' arrugginiti o non riuscite sempre a ricordare gli argomenti di comandi come `lsof` o `tar`?

Di certo non aiuta il fatto che la prima opzione spiegata in `man tar' sia:

```
-b bloccare
   Specificare la dimensione del blocco, in record da 512 byte, per l'I/O dell'unità nastro.
   Normalmente questo argomento è necessario solo quando si legge o si scrive sulle unità a nastro,
   e di solito nemmeno allora, dato che la dimensione predefinita del blocco di 20 record (10240 byte) è molto comune.
```

Sembra che ci sia spazio per pagine di aiuto più semplici che si concentrino su esempi pratici.
Che ne dite di:

![SVG animato del client tldr che mostra il comando tar](/tldr-tar.svg)

> La pagina TLDR per il comando tar si trova anche su questo sito web [questo link]("common/tar")

Questo repository è proprio questo: una raccolta di esempi in costante crescita.
per i più comuni strumenti a riga di comando UNIX, Linux, macOS, SunOS, Android e Windows.

## Che cos'è questo sito?

Lo scopo di questo sito è quello di rendere le Pagine TLDR, una raccolta di pagine di aiuto gestite dalla comunità
per gli strumenti a riga di comando_ agli utenti del web digitando semplicemente "Pagine TLDR + nome_comando" nel loro motore di ricerca preferito.

Attualmente, non è possibile trovare la pagina TLDR di un comando con una semplice ricerca su Google. La situazione è ancora peggiore quando si cerca un comando in una lingua specifica che non è l'inglese, perché spesso ci sono siti web lenti e clickbait.

Infatti, questo sito supporta anche i commenti e la condivisione, rendendo le pagine TLDR "amiche del web". 

### Analisi, monitoraggio e annunci

Ovviamente non ci sono **pubblicità**. 

Il tracciamento viene effettuato con Matomo. Matomo è impostato per non raccogliere **dati personali**[^1], quindi è conforme al GDPR e non richiede cookie banner. Se si desidera rinunciare, [è possibile farlo qui](https://stats.bortox.it/index.php?module=CoreAdminHome&action=optOut&language=it).

Il sito è **ospitato in Europa**, da PHP-Friends. Secondo il sito web-carbon.com, il centro dati utilizza **energia sostenibile**!

Se vuoi **sostenere** il sito (pago i server), puoi [**donare qualcosa qui**](https://bortox.it/contribuisci-cs-en).

### Perché questo sito?

1. indicizzare le pagine TLDR e renderle facilmente ricercabili online in più lingue
2. solo per scrivere qualcosa

### Come funziona questo sito?

* I file sorgente TLDR in Markdown e i dati Git associati sono letti da uno script (30m).
* Le pagine compatibili con Hugo sono create dallo script
* Hugo crea questo sito web (~6500 pagine) in soli 10 secondi!

### Possibili novità

- [ ] Pagine specifiche per gli impegni
- Traduzione automatica con DeepL (fino a 500.000 caratteri/mese nella versione gratuita)


## Come si usa

Un modo popolare e conveniente per accedere a queste pagine sul proprio computer
è installare il [client Node.js](https://github.com/tldr-pages/tldr-node-client),
che è supportato dai manutentori del progetto tldr-pages:

``sh
npm install -g tldr
```

In alternativa, si può usare il [client Python](https://github.com/tldr-pages/tldr-python-client), che può essere installato tramite `pip3`.

``sh
pip3 installare tldr
```

In questo modo si ha accesso diretto a una guida semplificata e di facile lettura per comandi come `tar`,
accessibile digitando `tldr tar` invece del normale `man tar`.

Se si desidera una versione offline senza installare alcun software,
vedere la [versione PDF](https://tldr.sh/assets/tldr-book.pdf).

Per navigare senza installare un client sul computer,
vedere il client web all'indirizzo <https://tldr.ostera.io>.

Ci sono anche **vari altri clienti** forniti dalla comunità,
sia per la riga di comando che per altre piattaforme.
Per un elenco completo dei clienti, consultare il nostro [wiki](https://github.com/tldr-pages/tldr/wiki/tldr-pages-clients).


## Come posso contribuire a tldr-pages?

Tutti i contributi sono benvenuti!

Alcuni modi per contribuire sono

- Aggiungete il vostro comando preferito che non è coperto.
- Aggiunta di esempi o miglioramento del contenuto di una pagina esistente.
- Aggiunta di pagine richieste dai nostri numeri con l'etichetta [help wanted](https://github.com/tldr-pages/tldr/issues?q=is%3Aopen+è%3Aissue+label%3A%22help+wanted%22).
- Tradurre le pagine in diverse lingue.

Tutte le pagine di `tldr` sono scritte in Markdown, quindi possono essere modificate abbastanza facilmente e le modifiche possono essere fatte in
con Git alla riga di comando o tramite il file
tramite l'interfaccia web di GitHub.

Ci sforziamo di mantenere una comunità [accogliente e collaborativa](GOVERNANCE.md).
Se è la prima volta che contribuisci, dai un'occhiata alle [Linee guida per i contributi](CONTRIBUTING.md) e inizia!

Se volete contribuire alle traduzioni, potete <https://lukwebsforge.github.io/tldri18n/>
per vedere lo stato di avanzamento generale di tutte le traduzioni e sapere quali traduzioni mancano o sono obsolete.

## Cosa significa "tldr"?

TL;DR sta per "Troppo lungo; non ho letto".
Deriva dal gergo di internet, dove si usa per indicare che un testo lungo (o parti di esso) è stato
(o parte di esso) è stato saltato perché troppo lungo.
Maggiori informazioni in [articolo] di How-To Geek (https://www.howtogeek.com/435266/what-does-tldr-mean-and-how-do-you-use-it/).

[^1]: Nessun registro dei visitatori, tracciamento senza cookie, indirizzi IP anonimizzati (2 byte, come 192.168.xxx.xxx ) secondo [guida ufficiale matomo](https://matomo.org/faq/new-to-piwik/how-do-i-use-matomo-analytics-without-consent-or-cookie-banner/) ... 