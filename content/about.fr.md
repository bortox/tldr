---
date: 2021-11-17
title: "A propos de TLDR Pages"
description: "Qu'est-ce que TLDR Pages ? Comment contribuer ? Qu'est-ce que ce site ?"
---

> Avertissement : cette page est traduite automatiquement - contrairement aux pages TLDR de ce site - il peut donc y avoir des erreurs de traduction.

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

## Qu'est-ce que tldr-pages ?

Le projet **tldr-pages** est une collection de pages d'aide maintenues de manière collaborative.
pour les outils en ligne de commande qui offrent un complément plus simple et plus accessible aux outils traditionnels.
aux traditionnelles [pages de manuel](https://en.wikipedia.org/wiki/Man_page).

Vous êtes peut-être nouveau dans le monde des lignes de commande ? Peut-être êtes-vous un peu rouillé ou ne vous souvenez pas toujours des arguments de commandes comme `lsof` ou `tar` ?

Cela n'aide certainement pas que la première option expliquée dans `man tar` soit :

```
-bloc b
   Spécifiez la taille du bloc, en enregistrements de 512 octets, pour les E/S du lecteur de bande.
   Normalement, cet argument n'est nécessaire que pour la lecture ou l'écriture sur des lecteurs de bande,
   et généralement même pas, car la taille de bloc par défaut de 20 enregistrements (10240 octets) est très courante.
```

Il semble qu'il y ait place pour des pages d'aide plus simples, axées sur des exemples pratiques.
Pourquoi pas :

![SVG animé du client tldr montrant la commande tar](/tldr-tar.svg)

> La page TLDR de la commande tar se trouve également sur ce site web [ce lien]("https://tldr.bortox.it/content/common/tar")

Ce référentiel n'est rien d'autre qu'une collection d'exemples en constante évolution.
pour les outils de ligne de commande les plus courants d'UNIX, Linux, macOS, SunOS, Android et Windows.

### Quel est ce site ?

Le but de ce site est de faire des pages TLDR, une collection de pages d'aide gérées par la communauté.
pour les outils en ligne de commande_ aux utilisateurs du web en tapant simplement "pages TLDR + nom_de_commande" dans leur moteur de recherche préféré.

Actuellement, il n'est pas possible de trouver la page TLDR d'une commande avec une simple recherche Google. La situation est encore pire lors de la recherche d'une commande dans une langue spécifique autre que l'anglais, car il y a souvent des sites lents et clickbait.

En fait, ce site prend également en charge les commentaires et le partage, ce qui rend les pages TLDR "conviviales". 

### Analyse, suivi et annonces

Bien sûr, il n'y a pas de **publicités**. 

Le suivi est effectué avec Matomo. Matomo est configuré pour ne pas collecter de **données personnelles**[^1], il est donc conforme au GDPR et ne nécessite pas de cookies de bannière. Si vous souhaitez vous désinscrire, [vous pouvez le faire ici](https://stats.bortox.it/index.php?module=CoreAdminHome&action=optOut&language=it).

Le site est **hébergé en Europe**, par PHP-Friends. Selon le site web-carbon.com, le centre de données utilise **l'énergie durable** !

Si vous voulez **soutenir** le site (je paie pour les serveurs), vous pouvez [**donner quelque chose ici**](https://bortox.it/contribuisci-cs-en).

### Pourquoi ce site ?

1. indexer les pages TLDR et les rendre facilement consultables en ligne dans plusieurs langues
2. juste pour écrire quelque chose

### Comment fonctionne ce site ?

* Les fichiers sources TLDR en Markdown et les données Git associées sont lus depuis un script (30m).
* Les pages compatibles avec Hugo sont créées par le script
* Hugo crée ce site web (~6500 pages) en seulement 10 secondes !

### Nouvelles fonctionnalités possibles

- [ ] Pages spécifiques à l'engagement
- Traduction automatique avec DeepL (jusqu'à 500 000 caractères/mois dans la version gratuite)


## Comment utiliser

Un moyen populaire et pratique d'accéder à ces pages sur votre propre ordinateur
est d'installer le [client Node.js](https://github.com/tldr-pages/tldr-node-client),
qui est soutenu par les mainteneurs du projet tldr-pages :

``sh
npm install -g tldr
```

Alternativement, vous pouvez utiliser le [client Python](https://github.com/tldr-pages/tldr-python-client), qui peut être installé via `pip3`.

``sh
pip3 install tldr
```

Cela vous donne un accès direct à un guide simplifié et facile à lire pour les commandes telles que `tar`,
accessible en tapant `tldr tar` au lieu du normal `man tar`.

Si vous voulez une version hors ligne sans installer de logiciel,
voir la [version PDF](https://tldr.sh/assets/tldr-book.pdf).

Pour naviguer sans installer un client sur votre ordinateur
voir le client web à <https://tldr.ostera.io>.

Il y a également **divers autres clients** fournis par la communauté,
à la fois pour la ligne de commande et pour les autres plateformes.
Pour une liste complète des clients, consultez notre [wiki](https://github.com/tldr-pages/tldr/wiki/tldr-pages-clients).

## Que signifie 'tldr' ?

TL;DR signifie "Trop long ; je n'ai pas lu".
Ce terme est issu du jargon de l'Internet, où il est utilisé pour indiquer qu'un long texte (ou des parties de celui-ci) a été...
(ou des parties de celle-ci) a été sautée car elle est trop longue.
Plus d'informations dans [article] par How-To Geek (https://www.howtogeek.com/435266/what-does-tldr-mean-and-how-do-you-use-it/).

[^1] : Pas de journal des visiteurs, suivi sans cookies, adresses IP anonymes (2 octets, comme 192.168.xxx.xxx ) selon le [guide officiel du matomo](https://matomo.org/faq/new-to-piwik/how-do-i-use-matomo-analytics-without-consent-or-cookie-banner/) ... 


## Comment puis-je contribuer à tldr-pages ?

Toutes les contributions sont les bienvenues !

Voici quelques façons de contribuer

- L'ajout de votre commande préférée qui n'est pas traitée.
- L'ajout d'exemples ou l'amélioration du contenu d'une page existante.
- Ajouter des pages demandées de nos éditions avec l'étiquette [help wanted](https://github.com/tldr-pages/tldr/issues?q=is%3Aopen+is%3Aissue+label%3A%22help+wanted%22).
- Traduction de pages en différentes langues.

Toutes les pages de `tldr` sont écrites en Markdown, de sorte qu'elles peuvent être éditées assez facilement et les modifications peuvent être faites en
avec Git sur la ligne de commande ou via
via l'interface web GitHub.

Nous nous efforçons de maintenir une communauté [accueillante et collaborative](GOVERNANCE.md).
Si vous contribuez pour la première fois, jetez un coup d'œil aux [directives de contribution](CONTRIBUTING.md) et lancez-vous !

Si vous souhaitez contribuer à des traductions, vous pouvez consulter <https://lukwebsforge.github.io/tldri18n/>
pour voir la progression globale de toutes les traductions et savoir quelles traductions sont manquantes ou obsolètes.
