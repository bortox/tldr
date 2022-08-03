---
date: 2021-11-17
title: "Sobre as Páginas TLDR"
description: "O que são as Páginas TLDR? Como contribuir? O que é este sítio web?"
---

> Atenção: esta página é automaticamente traduzida - ao contrário das Páginas TLDR neste website - por isso pode haver erros de tradução

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

## O que é tldr-páginas?

O projeto **tldr-páginas*** é uma coleção de páginas de ajuda mantidas colaborativamente
para ferramentas de linha de comando que proporcionam um complemento mais simples e acessível aos
tradicional [man pages](https://en.wikipedia.org/wiki/Man_page).

Talvez você seja novo no mundo das linhas de comando? Talvez você esteja um pouco enferrujado ou nem sempre consegue se lembrar dos argumentos para comandos como 'lsof' ou 'tar'?

Certamente não ajuda que a primeira opção explicada em `man tar` seja:

```
-b bloco
   Especifique o tamanho do bloco, em registros de 512 bytes, para E/S de unidade de fita adesiva.
   Normalmente, este argumento só é necessário quando se lê ou escreve em unidades de fita adesiva,
   e geralmente nem mesmo assim, já que o tamanho padrão do bloco de 20 registros (10240 bytes) é muito comum.
```

Parece haver espaço para páginas de ajuda mais simples que se concentrem em exemplos práticos.
Que tal:

![SVG animado do cliente tldr mostrando o comando tar](/tldr-tar.svg)

> A página TLDR para o comando do alcatrão também pode ser encontrada neste site (este link)(https://tldr.bortox.it/content/common/tar)

Este repositório é exatamente isso: uma coleção de exemplos em constante crescimento.
para as ferramentas mais comuns de linha de comando UNIX, Linux, MacOS, SunOS, Android e Windows.

## O que é este site?

O objetivo deste site é fazer das Páginas TLDR, uma coleção de páginas de ajuda administradas pela comunidade
para ferramentas de linha de comando_ para usuários da web simplesmente digitando 'TLDR pages + command_name' em seu mecanismo de busca preferido.

Atualmente, não é possível encontrar a página TLDR de um comando com uma simples busca no Google. A situação é ainda pior quando se procura por um comando em um idioma específico que não seja o inglês, porque muitas vezes há sites lentos e clickbait.

Na verdade, este site também suporta comentários e compartilhamento, tornando as páginas TLDR 'amigáveis'. 

### Análise, monitoramento e anúncios

É claro que não há **apublicidade***. 

O rastreamento é feito com a Matomo. A Matomo está configurada para não coletar ** dados pessoais**[^1], portanto, está em conformidade com a GDPR e não requer cookies de banner. Se você deseja optar por não participar, [você pode fazê-lo aqui](https://stats.bortox.it/index.php?module=CoreAdminHome&action=optOut&language=it).

O site é **hospedado na Europa**, por PHP-Friends. Segundo a web-carbon.com, o centro de dados utiliza **energia sustentável**!

Se você quiser **apoiar** o site (eu pago pelos servidores), você pode [**donar algo aqui***](https://bortox.it/contribuisci-cs-en).

### Por que este site?

1. Indexar páginas TLDR e torná-las facilmente pesquisáveis on-line em vários idiomas
2. Apenas para escrever algo

### Como funciona este site?

* Os arquivos fonte TLDR em Markdown e dados Git associados são lidos a partir de um script (30m).
* As páginas compatíveis com Hugo são criadas pelo roteiro
* Hugo cria este website (~6500 páginas) em apenas 10 segundos!

### Possíveis novas características

- [ ] Páginas específicas do compromisso
- Tradução automática com DeepL (até 500.000 caracteres/mês na versão gratuita)


## Como usar

Uma maneira popular e conveniente de acessar estas páginas em seu próprio computador
é instalar o [cliente Node.js](https://github.com/tldr-pages/tldr-node-client),
que é apoiado pelos mantenedores do projeto tldr-pages:

``sh
npm instalar -g tldr
```

Alternativamente, você pode utilizar o [cliente Python](https://github.com/tldr-pages/tldr-python-client), que pode ser instalado via `pip3`.

``sh
pip3 instalar tldr
```

Isto lhe dá acesso direto a um guia simplificado e de fácil leitura de comandos como o `tar`,
acessível digitando `tldr tar` em vez do normal `man tar`.

Se você quiser uma versão offline sem instalar nenhum software,
ver a [versão PDF](https://tldr.sh/assets/tldr-book.pdf).

Para navegar sem instalar um cliente em seu computador
ver o cliente web em <https://tldr.ostera.io>.

Há também **vários outros clientes*** fornecidos pela comunidade,
tanto para a linha de comando como para outras plataformas.
Para uma lista completa de clientes, consulte nosso [wiki](https://github.com/tldr-pages/tldr/wiki/tldr-pages-clients).


## Como posso contribuir para as páginas tldr?

Todas as contribuições são bem-vindas!

Algumas formas de contribuir são

- Adicionando seu comando favorito que não está coberto.
- Adicionar exemplos ou melhorar o conteúdo de uma página existente.
- Adicionando páginas solicitadas de nossas edições com a etiqueta [ajuda desejada](https://github.com/tldr-pages/tldr/issues?q=is%3Aopen+is%3Aissue+label%3A%22help+wanted%22).
- Tradução de páginas em diferentes idiomas.

Todas as páginas `tldr` são escritas em Markdown, de modo que podem ser editadas com bastante facilidade e as alterações podem ser feitas em
com Git na linha de comando ou através do
através da interface web GitHub.

Nós nos esforçamos para manter uma comunidade [acolhedora e colaborativa](https://github.com/tldr-pages/tldr/blob/main/GOVERNANCE.md).
Se você é um contribuinte pela primeira vez, dê uma olhada nas [Diretrizes de Contribuição](https://github.com/tldr-pages/tldr/blob/main/CONTRIBUTING.md), e comece!

Se você gostaria de contribuir para as traduções, você pode <https://lukwebsforge.github.io/tldri18n/>
para ver o progresso geral de todas as traduções e saber quais traduções estão faltando ou desatualizadas.

## O que significa 'tldr'?

TL;DR significa "Too long; I have not read" (Tempo demais; não li).
Deriva do jargão da internet, onde é usado para indicar que um texto longo (ou partes dele) foi
(ou partes dele) foi pulado porque é muito longo.
Mais informações em [artigo] por How-To Geek (https://www.howtogeek.com/435266/what-does-tldr-mean-and-how-do-you-use-it/).

[^1]: Nenhum registro de visitante, rastreamento sem cookies, endereços IP anônimos (2 bytes, como 192.168.xxx.xxx ) de acordo com [guia oficial do matomo](https://matomo.org/faq/new-to-piwik/how-do-i-use-matomo-analytics-without-consent-or-cookie-banner/) ... 